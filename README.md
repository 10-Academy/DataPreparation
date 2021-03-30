
# Data Preparation

## What is Data Preparation

**Data Preparation** is a pre-processing step in which data from one or more sources is cleaned and transformed to improve its quality prior to its use in business analytics. It is the process of gathering, cleaning, and consolidating data into a single file or data table, primarily for use in analysis or predictive modelling.

It is rare that you get data in exactly the right form you need it. Often you’ll need to create some new variables, rename existing ones, reorder the observations, or just drop registers in order to make data a little easier to work with.

This is called data wrangling (or preparation), and it is a key part of Data Science. Most of the time, data you have can’t be used straight away for your analysis: it will usually require some kind of manipulation and adaptation, especially if you need to aggregate other sources of data to the analysis.

In essence, raw data is messy (usually unusable at the start), and you’ll need to roll up your sleeves to get to the right place. For this reason, all the activity you take to make it “neat” enough is as important as the algorithms you choose to work with. In almost all cases, the data-wrangling piece is a prerequisite to the math/modelling and a majority of the time is spent on cleaning the data in a real-world scenario. [learn more here](https://towardsdatascience.com/the-basics-of-data-prep-7bb5f3af77ac)

## How will I use Data Preparation in my ML career?  What is the importance of Data Preparation in a data science project
It is undeniable that 80% of a data scientist’s time and effort is spent in collecting, cleaning and preparing the data for analysis because datasets come in various sizes and are different in nature. It is extremely important for a data scientist to reshape and refine the datasets into usable datasets, which can be leveraged for analytics. 

Suppose you are trying to understand at what day of the week do the members of a slack workspace you belong to send the most message and what are the most common emojis that are being used and who is using them or which channel sees the most message and who the most tagged members are? To answer these questions, analysis needs to be performed on the slack data. The first task would be gathering the data using slack API, then cleaning aka preparing the data. As the data would be provided via an API, it needs to be formatted into a nice format that will make the analysis easy and all insights that would be generated from the data would be accurate and correct. All these process can be termed as data preparation.

CrowdFlower, provider of a “data enrichment” platform for data scientists, conducted a survey of about 80 data scientists and found that data scientists spend –
<ul>
  <li>60% of the time in organizing and cleaning data</li>
  <li>19% of the time is spent in collecting datasets</li>
  <li>9% of the time is spent in mining the data to draw patterns</li>
  <li>3% of the time is spent in training the datasets</li>
  <li>4% of the time is spent in refining the algorithms</li>
  <li>5% of the time is spent in other tasks</li>
</ul>
The survey statistics clearly shows that most of the data scientist’s time is spent in data preparation (collecting, cleaning, transforming and organizing) before they can begin doing data analysis. There are several valuable data science tasks like data exploration and visualization, data modelling etc. but the less glamorous and least enjoyable data science task - is data preparation. Data preparation is also referred as data wrangling, data munging or data cleaning. The amount of time needed for data preparation for a particular analysis problem, directly depends on the health of the data i.e. how complete it is, how many missing values are there, how dirty it is and the various kinds inconsistencies or irregularities present in the data.

## Why it is important to learn Data Preparation before starting my career?
According to a Gartner research report, poor quality of data or bad data costs an average organization $13.5 million every year, which is too high a cost to bear. Bad data or poor quality of data can alter the accuracy of insights or could lead to incorrect insights, which is why data preparation or data cleaning is of utmost importance even though it is time consuming and the least enjoyable task of the data science process.

Need for Data Cleaning or Data Preparation

1. Dataset might contain discrepancies in the names or codes.
2. Dataset might contain outliers or errors.
3. Dataset lacks your attributes of interest for analysis.
4. All in all the dataset is not qualitative but is just quantitative.

++Understanding Garbage In, Garbage Out

## How Data Preparation helps to make Machine Learning work
++List out typical problems that arise with dirty data
++List out information that may be missing without 'cleaned' data
++List out 

## How Data Preparation is part of your daily life
++A few good examples
++APIs and how they take care of some automated data flows?

## What components make up Data Prep // Which steps to execute a data preparation task?
There is no rigid way of doing data preparation task as different datasets requires different ways of getting a clean, nicely formatted data. It all depends on the state of the data. Generally, it could involve the following process:
1. Preparing for the preparation:: This stage is known as data gathering or data collection. You can't clean what you don't have right? The process may invlove [collecting data from a database](https://www.w3schools.com/python/python_mysql_getstarted.asp), [scraping a website](https://realpython.com/beautiful-soup-web-scraper-python/) for any kind of data, [extracting sheet from an excel documents](https://towardsdatascience.com/replacing-sheets-with-python-f1608e58d2ca) etc. Having access to the data, you can move to the next phase of data preparation which is Exploratory Data Analysis
2. Exploratory Data Analysis:: (EDA) for short is a very important stage in any data preparation task. It enables you to understand the structure of any data, make sense of the data, detect outliers, detect features with missing values, identify unwanted features and invalid datapoints etc. This stage generally is divided into 2 the Uni-variate Analysis and Bi-variate Analysis and you can learn more about them in the repository [here](https://github.com/10-Academy-Self-Learning-Resources/DataVisualization)
3. Data Preprocessing:: While Exploring the data, you would have identified columns/features with problems (invalid values, missing values, outliers etc). Preprocessing the data can involve dropping columns, removing outliers, replacing values etc. It sometimes important to have a domain knowledge about what the data is trying to describe, this can help preprocess the data and generate useful, important insights.
4. Data Transformation:: This stage is about changing a particular feature into another dimension or scale. For examples, transforming a population(Million scale) feature to a unit scale. This is neccessary because the model will assign higher weights to the bigger values and by so doing introduces biasness to the model thereby getting a wrong interpretation or prediction. Learn more about [data transformation here](https://towardsdatascience.com/normalization-vs-standardization-quantitative-analysis-a91e8a79cebf)

The final part could be to build a model with the data or save it for another use or just generate more insights and present findings to stackholders. Whichever the case you have a nicely formatted, clean data ready for further analysis.


## What differentiates beginners from experts in this competency?
++I don't know

## Learn More 
1. [7 steps of data Preparation](https://www.kdnuggets.com/2019/06/7-steps-mastering-data-preparation-python.html)
2. [Doing Data Science: A Kaggle Walkthrough Part 3 – Cleaning Data, by Brett Romero](https://www.kdnuggets.com/2016/06/doing-data-science-kaggle-walkthrough-data-cleaning.html)
3. [Machine Learning Workflows in Python from Scratch Part 1: Data Preparation](https://www.kdnuggets.com/2017/05/machine-learning-workflows-python-scratch-part-1.html)
4. [Introduction to Logarithm and Exponential Functions](https://nool.uoit.ca/mathematics/exponential-logarithmic-functions/basics/index.php)
5. [Techniques to Handle Imbalaced Datasets](https://www.kdnuggets.com/2017/06/7-techniques-handle-imbalanced-data.html)

![data_prep](https://user-images.githubusercontent.com/40719064/112724545-2f437500-8f14-11eb-8aa0-fc50da2c42a5.jpg)
