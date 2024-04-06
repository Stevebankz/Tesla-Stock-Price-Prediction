# Tesla Stock Price Prediction using Machine Learning

## 📊 **Overview**

This project focuses on predicting Tesla stock prices using machine learning techniques. It involves reading data from a CSV file ('TSLA.csv'), analyzing trends, visualizing the closing price trend, and training machine learning models for prediction.

## 📈 **Data Analysis and Visualization**

- Reading the CSV file 'TSLA.csv' into a pandas DataFrame.
- Displaying the first few rows of the DataFrame to inspect the data.
- Plotting the closing price trend with customized visualizations.
  - Setting plot figure size, unique color, and linestyle.
  - Adding title, labels, and customizing gridlines.
  - Adding a horizontal line at the average closing price for reference.
  - Adding a legend to the plot.

- 💻 Dataset : https://www.kaggle.com/datasets/timoboz/tesla-stock-data-from-2010-to-2020

## 🔍 **Observations**

- Prices tend to be higher at quarter ends compared to non-quarter end months.
- Trade volume is lower at quarter ends.
- Additional columns are added to aid model training, including the target feature indicating whether to buy or not.
- Checking for feature correlation and ensuring balance in the target feature.

## 🤖 **Machine Learning Model Training**

- Training state-of-the-art machine learning models (Logistic Regression, Support Vector Machine, XGBClassifier).
- Evaluating model performance on training and validation data.
- Utilizing the ROC-AUC curve as an evaluation metric to measure prediction accuracy.
- Acknowledging that achieved accuracy may not surpass random guessing due to data limitations or model complexity.

## 📉 **Conclusion**

The project aims to leverage machine learning techniques to predict Tesla stock prices. Despite efforts in feature engineering and model training, the accuracy achieved by the models may not exceed random guessing. Future improvements may involve acquiring more data or exploring advanced modeling techniques.
 
