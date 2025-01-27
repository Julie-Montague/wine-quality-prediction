# wine-quality-prediction
This is a supervised learning project that makes use of the wine quality data set from kaggle. The objective is to predict whether a wine quality is good or bad using various classification models. From the dataset, the qine quality has 7 ratings ranging from 3 to 9 where 3 is ranked as very poor quality while 9 is very hugh quality. For this project, I converted the problem from a multi-classification problem to a binary classification problem where ratings less than or equal to 6 are classified as 0 (poor quality) and ratings greater tha 6 are classified as 1(good quality)

## Models Compared
- Random Forest
- XGBoost
- Logistic Regression
- LightGBM

## Evaluation Matric
Accuracy Score

## Package Dependencies
- pandas
- numpy
- seaborn
- matplotlib
- statsmodels
- sklearn
