# Online-Shoppers-Purchasing-Intention
This repository is the result of analysis and prediction of dataset "Online Shoppers Purchasing Intention" which is presented in Bahasa Indonesia by ec-Team for Final Project of Data Science Batch 30 Rakamin Academy. 

The goal of this project is to increase the conversion rate of online shopping site visitors into customers leading to increased sales and revenue through analyzing visitor behavior and predicting the visitors who are likely to purchase using classification - machine learning algorithms. The results show that page values has the greatest impact on a visitor's purchase decision. The conversion rate to purchase increases up to 31.7% by applying model and actionable recommendation from insights.

Dataset: Online Shoppers Purchasing Intention, UCI Machine Learning, 2018 [[source]](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset)

Tools: Python - JupyterLab

Libraries: Pandas, Numpy, Matplotlib, Seaborn, Scipy, Scikit-learn, Imbalanced-learn, Shap

### Summary of the analysis

- This dataset has 12330 observations and 18 variables with 9 numerical features, 8 categorical features and one target feature.
- All numerical variables have a right-skewed distribution and contain a lot of outliers.
- Revenue is the target variable that labels a visitor's purchase decision either purchase (class True) or not purchase (class False) with only 15% of total visitors who make a purchase.
- From exploratory data analysis, visitors with low exit and bounce rates and high page values, tend to make a purchase.
- Based on data characteristics, the selected algorithm to build a classification model is Gradient Boosting Classifier.
- The result shows that page values are the biggest impact on visitors' purchase decisions. The conversion rate to purchase increases up to 31.7% by applying model and actionable recommendation from insights.

### What I have learned

- Framing the business problem.
- Create a machine learning model and extract insight from it to make an actionable recommendation for the business team.
- Make a business simulation from insights that calculate the increase in the conversion rate.

### File Dictionaries

- [SourceCode_Final_ecTeam.ipynb](https://github.com/miramlr/Online-Shoppers-Purchasing-Intention/blob/50665ad8e76230a7de3b8d03b156e40a035d4da9/Final%20Project_ec-Team.pdf): this notebook contains all of project details, such as business understanding, exploratory data analysis & insights, data preprocessing and modeling.
- [Final Project_ec-Team.pdf](https://github.com/miramlr/Online-Shoppers-Purchasing-Intention/blob/50665ad8e76230a7de3b8d03b156e40a035d4da9/SourceCode_Final_ecTeam.ipynb): summary of the project.
- [requirements.txt](https://github.com/miramlr/Online-Shoppers-Purchasing-Intention/blob/50665ad8e76230a7de3b8d03b156e40a035d4da9/requirements.txt): list of used libraries with its version.
