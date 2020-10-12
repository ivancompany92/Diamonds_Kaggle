# Data Project README file

![Image](https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/styles/1200/public/media/image/2018/08/fabricar-diamantes.jpg?itok=XMn4mQSi)

#### Ivan Company

#### Data Analytics Bootcamp - Project module 3


## **Overview**
In this project, after having analyzed the diamonds in the previous module, we are going to create a Machine Learning model to find out the price of a diamond.

For them we are going to create new columns in our diamond DF with the new characteristics that we have detected, such as the volume of the diamond, shape, the logarithm of carat ...

Using an **"LGBMRegressor"** and **"RandomizedSearchCV"** model I was able to obtain the best hyperparameters with which I obtained the lowest RMSE value of the kaggle competition and I was **First** of my course!!


## **Data**

* [.csv Dataset](https://www.kaggle.com/c/dataptmad0420/data)

The dataset are the diamonds_train.csv, with ten columns where you can see all the information about each diamond, and diamonds_predict.csv, where we have the information of the diamonds that we have to predict the value. 

We have 40.455 diamonds in our diamonds_train.csv and 13.485 diamonds in our diamonds_predict.csv


## **Requirements**
You need to have Python installed with the following libraries:
   - Pandas
    
   - numpy
    
   - lightgbm
   
   - scikit-learn   


You have more information in the file: requirements.txt


### **Folder structure**
```
└── project
    ├── .gitignore
    ├── requeriments.txt
    ├── README.md
    ├── notebooks
    │   └──diamond_model.ipynb
    ├── submissions
    └── data
        └── diamonds_train.csv
        └── diamonds_predict.csv
```

## **Kaggle competition**
You can see the Kaggle competicion in this [link](https://www.kaggle.com/c/dataptmad0420/overview)

## **Next steps:**
- We can cluster the diamonds with kMeans or DBSCAN to better group the diamonds according to their characteristics and then train the model with that information to improve the prediction of the value of each diamond.
