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

1. Data Exploration

I began with some light data exploration using basic commands (.describe(), .info(), value counts) and to understand the nature of the data.
I seperated the data into categorical and numerical.
Used histograms for categorical data, came out quite messy and skewed. Only able to normalise one feature (Fare) with a log function.

![image](https://github.com/rx229/Tony_Portfolio/blob/main/Titanic/Images/skewed.png)


2. Exploratory Data Analysis

- Correlation between feautres
- Feature engineering

3. Data Preprocessing

- Dropping Null values
- Imputing data

4. ML Modelling

- Model Building

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rx229/Tony_Portfolio/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
