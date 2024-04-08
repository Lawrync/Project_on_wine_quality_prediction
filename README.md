#  Project_on_wine_quality_prediction


![istockphoto-452113115-612x612](https://github.com/Lawrync/Project_on_wine_quality_prediction/assets/142001815/0e19daf3-f72d-4cb8-ad49-c0d752be74a5)       


###  Business Understanding:

1)intoduction

The dataset comprises physicochemical properties and sensory data of red Vinho Verde wine. It offers an opportunity for predictive modeling, posing as a classification or regression task. The objective is to leverage machine learning to identify the physicochemical features contributing to wine quality perception, aiming to uncover insights into factors affecting wine quality.

##  Problem Statement:

This project aims to utilize machine learning to predict wine quality based on its physicochemical attributes. The goal is to develop a model that accurately classifies or predicts the quality score, ranging from 0 to 10, using the provided input variables.

3) Metrics of Success:

Success will be measured by the accuracy of the machine learning model in predicting wine quality, along with evaluation metrics like precision, recall, and F1-score. A target AUC of 0.88 is set as a benchmark for model performance.

4) Research Questions:

1. Identify significant physicochemical properties influencing red wine quality.
2. Evaluate machine learning's effectiveness in predicting red wine quality based on physicochemical attributes.
3. Compare the impact of different machine learning algorithms on predictive performance.
4. Determine the optimal cutoff for classifying wines as 'good' or 'not good' based on quality scores.

##  5) Objectives:

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
![image](https://github.com/Lawrync/Project_on_wine_quality_prediction/assets/142001815/02f7b3ba-7d33-491a-b5a5-c70989f227d3)



The histogram displays the distribution of fixed acidity in the dataset, with the x-axis representing acidity levels from 4 to 16 and the y-axis showing frequency up to 300. A bell-shaped curve overlaid on the bars indicates a normal distribution, peaking around an acidity level of 8.

![image](https://github.com/Lawrync/Project_on_wine_quality_prediction/assets/142001815/28817bfa-5df6-4fe1-b444-bc652f3c6baa)





The scatter plot titled "Fixed Acidity vs. Citric Acid" illustrates the relationship between these two variables in wines. The x-axis represents "Fixed Acidity" (ranging from 5 to 16), while the y-axis represents "Citric Acid" (ranging from 0 to 1). Each data point represents a wine sample, color-coded by its quality level (ranging from 3 to 8). Observations indicate clustering of data points between fixed acidity levels of 6 to 10 and citric acid levels of 0.2 to 0.6. Notably, quality levels 5 and 6 have the highest concentration of data points, while levels 8 and 9 are sparsely represented. This scatter plot effectively visualizes the relationship between fixed acidity, citric acid, and wine quality.


![image](https://github.com/Lawrync/Project_on_wine_quality_prediction/assets/142001815/152d83d9-5a59-4fba-b2c7-8225c9c81e30)


#  Model Building

