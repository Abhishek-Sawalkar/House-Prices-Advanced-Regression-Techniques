# House-Prices-Advanced-Regression-Techniques
## Problem Statement Definition

We are asked to **predict sale prices for residential real estate properties** from describing features. We have a training set with 1460 observations and corresponding prices. We need to make predictions for 1459 observations where the price is not known to us.

><span style="color:darkgreen">**Our goal is to use the Ames Housing data set to build a machine learning model that can predict the sale price of a residential property.**

The data in the training set includes the sale price, which makes this **a supervised regression machine learning task**:

>**Supervised**: We have access to both the features and the target and our goal is to train a model that can learn a mapping between the two.  
>**Regression**: The sale price is a continuous variable.

Ideally we want to develop a model that is both **accurate** — it can predict the sale price close to the true value — and **interpretable** — we can understand the model predictions. 

## I have followed these steps:

1. Exploratory data analysis (EDA)
2. Data cleaning and formatting
3. Feature engineering
4. Try and compare various machine learning models on a performance metric
5. Perform hyperparameter tuning for most promising models
6. Train best models on full data set and submit predictions

In **data cleaning and formatting** will especially take care of:

- Missing values
- Wrong values
- Wrong datatypes
- Outliers
- Skewed distributions
