# House Prices Kaggle Competition

House Prices - Advanced Regression Techniques 

https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview

I run through the entire machine learning project structure on the House Prices dataset in the Jupyter Notebook [(kaggle-house-prices-dataset.ipynb)](kaggle-house-prices-dataset.ipynb).

Top 5% of leaderboard.

![image](https://user-images.githubusercontent.com/41022783/137567388-7ce208d5-2521-4a58-9cc7-5004c864cd86.png)
![image](https://user-images.githubusercontent.com/41022783/137567416-3d98696d-302d-4098-8dec-0b3790cd9ee2.png)

## The Big Picture and Framing the Problem

This dataset comes from the House Prices - Advanced Regression Techniques Kaggle competition. The goal is to build a model that is able to predict the sale price of houses in Ames, Iowa, based on a variety of numerical and categorical features that describe many aspects of a residential home. 

In a real world application the goal would likely be to approach and surpass the predictive performance of expert realtors. The model could be used to determine the sale price of a house being put up for sale in that area. There might be certain limitations as to how the data is preprocessed and which model is chosen, as well as when the performance is good enough. However, seeing as this is a competition, the goal is to minimize the error in predictions using whatever means possible (without cheating of course). 

We will be predicting numerical prices based on data that comes with labels, therefore this is a supervised regression problem. The root mean squared error of the predictions on the holdout set will be used to measure performance before making predictions on the unlabeled test set. 

## Data Collection