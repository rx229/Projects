### Welcome to my portoflio

I will be using this page to document my progress in machine learning and data science.

Data science is generally focused on solving 1 of 3 different problems:

**Supervised Learning:**
-	Classification: Classifying labeled data
-	Regression: Predicting trends using previous labeled data

**Unsupervised Learning:**
-	Clustering: Finding patterns and groupings in unlabeled data




### Project 1 : [Titanic - Machine Learning from Disaster](https://github.com/rx229/Tony_Portfolio/tree/main/Titanic)

*"Use the Titanic passenger data (name, age, price of ticket, etc) to try to predict who will survive and who will die"* - [Kaggle](https://www.kaggle.com/c/titanic)

My first project is a classification problem where I try to predict a binary outcome (whether a passenger on the titanic survives). The project was to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data.

This was accomplished using Python in a [Jupyter Notebook](https://github.com/rx229/Tony_Portfolio/blob/main/Titanic/Titanic.ipynb). 

**Project Steps**

1. **Data Exploration**

I began with some light data exploration using basic commands (.describe(), .info(), value counts) and to understand the nature of the data. There were quite a few null values in the data sets.
I seperated the data into categorical and numerical.
Used histograms for categorical data, came out quite messy and skewed. Only able to normalise one feature (Fare) with a log function.


![image](https://github.com/rx229/Tony_Portfolio/blob/main/Titanic/Images/skewed.png)

![image](https://github.com/rx229/Tony_Portfolio/blob/main/Titanic/Images/normal.png)

Used a correlation matrix to observe correlations between features

![image](https://github.com/rx229/Tony_Portfolio/blob/main/Titanic/Images/Correlation%20Matrix.png)

2. **Exploratory Data Analysis**

I broke down several categorical features that had too many variables (Name, Cabin Number and Ticket Number) and tried to extract some meaningful data from the strings. For example I created the Title feature by extracting the title from the Name feature and compared surival rates.

![image](https://github.com/rx229/Tony_Portfolio/blob/main/Titanic/Images/Feature.PNG)

3. **Data Preprocessing**

I had to drop two rows as it has null values in a catergorical feature (Embarked) and imputed missing nurmeric data (Age, Fare) by calculating the mean.
I chose to encode data with OHE over pd.get_dummies as it gave differing number of features between test and training data. I didn't want to manually fix feature lengths. 

4. **ML Modelling**

I used Random Forest Algorith to produce the final output.

![image](https://github.com/rx229/Tony_Portfolio/blob/main/Titanic/Images/Results.PNG)

