# DSND-Starbucks-Project
###  Description 

Our Data set is divided into Three parts all shown below, Portfolio Data set contains information about the offers that Starbucks created and will send to users which consists of the channels of distribution, how much you need to expend to get the offer, how long will it be there, what is the offer, example Buy one Get one, and what is the reward you are going to get, 2nd data set consists of information about the users or the customers of Starbucks, their age, gender, income etc., and the last but not least is the transcript data set which is tracking the details of all transactions taking place from who, reviewed the offer, who viewed it and who completed it etc., we will go through the three data sets and look in details into each one of them to be able to know which features are more valuable for our analysis.

### Motivation
understand how customers respond to offers by building a model by 1st applying data analysis to understand the data and grasp the needed preparations to make the data ready for modeling, then prepare the data by data wrangling and preprocessing, analysing and visualizing important aspects of the data for insights and then apply several models to know what works well and what doesn't.

###  Libraries:
- Pandas
- Numpy
- Matplotlib
- seaborn
- Scikitlearn

###  Data sets:
- portfolio.json
- profile.json 
- transcript.json 

### RESULTS:
- There are more male customers than there are female customers
- Males are more likely to view and complete offers.
- The most common offer type among both genders is the BOGO offer then the discount offer ,and the least is the informational offer
- the year that added customers the most is the year 2017
- Customers with salaries more than 100k are mostly females
- average salaries for all age groups are 50k to 100k
- ML model to predict who will view and who will complete the offer

### Notes 
I discussed the findings and more in details throughout the notebook, and also the link below os for a blog post explaining the project
https://medium.com/@mohammadalsayedrouk/how-much-do-we-love-starbucks-offers-b6b3ecafdcbb?sk=26050ad21e59067a04f582b0879baae9

### resources
- https://github.com/wesm/pydata-book
- https://jakevdp.github.io/PythonDataScienceHandbook/
- https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.to_datetime.html
- https://benalexkeen.com/mapping-categorical-data-in-pandas/
- https://scikit-learn.org/stable/modules/svm.html
- https://scikit-learn.org/stable/modules/tree.html
- https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
