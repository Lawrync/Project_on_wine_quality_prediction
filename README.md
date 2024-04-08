##Project_on_wine_quality_prediction
![Uploading istockphoto-452113115-612x612.jpg…]()

###Business Understanding:

1)intoduction

The dataset comprises physicochemical properties and sensory data of red Vinho Verde wine. It offers an opportunity for predictive modeling, posing as a classification or regression task. The objective is to leverage machine learning to identify the physicochemical features contributing to wine quality perception, aiming to uncover insights into factors affecting wine quality.

##Problem Statement:

This project aims to utilize machine learning to predict wine quality based on its physicochemical attributes. The goal is to develop a model that accurately classifies or predicts the quality score, ranging from 0 to 10, using the provided input variables.

3) Metrics of Success:

Success will be measured by the accuracy of the machine learning model in predicting wine quality, along with evaluation metrics like precision, recall, and F1-score. A target AUC of 0.88 is set as a benchmark for model performance.

4) Research Questions:

1. Identify significant physicochemical properties influencing red wine quality.
2. Evaluate machine learning's effectiveness in predicting red wine quality based on physicochemical attributes.
3. Compare the impact of different machine learning algorithms on predictive performance.
4. Determine the optimal cutoff for classifying wines as 'good' or 'not good' based on quality scores.

##5) Objectives:

Main Objective:
Develop a machine learning model to predict red wine quality.

##other objectives 

1) Identify Key Physicochemical Properties:

- Analyze dataset to pinpoint significant physicochemical properties.
- Conduct feature selection or extraction to emphasize relevant variables.
2) Evaluate and Compare Machine Learning Algorithms:
  
- Train various machine learning algorithms and compare their performance.
- Use metrics like accuracy, precision, recall, F1-score, and AUC for comparison.
3) Establish Optimal Classification Threshold:
  
- Experiment with different classification thresholds to effectively classify 'good' and 'not good' wines.
- Determine threshold maximizing model accuracy in wine quality classification.
4) Enhance Understanding of Wine Quality Factors:
  
- Conduct exploratory data analysis (EDA) to visualize physicochemical properties' distribution.
- Derive insights into factors contributing to high-quality wine.

  ### Data Understanding:
  
The dataset contains 12 columns, including 11 physicochemical input variables (e.g., acidity, sugar content) and 1 output variable representing wine quality scores ranging from 0 to 10. The dataset allows for regression or classification tasks, suggesting the use of an arbitrary cutoff to classify wines as 'good' or 'not good.' Tips are provided for data preprocessing, feature engineering, and model evaluation.

1. Data Wrangling

Here we will work on data cleaning, handling missing values, data transformation, handling duplicates, data reshaping, and other processes to ensure that we have a clean, structured, and suitable format for analysis and modeling

2. Exploratory Data Analysis (EDA)

   The bar graph presents the distribution of wine quality ratings, with the x-axis representing quality scores from 5 to 9 and the y-axis indicating the count of wines within each quality category. The majority of wines fall into the 5 and 6 quality ratings, each accounting for approximately 700 counts, while there is a noticeable drop in wines rated 7. Wines rated 8 and 9 are scarce, with only a few instances recorded. Overall, the dataset predominantly consists of wines of average quality, with exceptionally high-quality wines being rare.
![Uploading image.png…]()

