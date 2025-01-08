# 04_Ice_SalesEDA

## About this Project

The Ice Sales EDA project looks at a synthetic dataset of sales data for video game from 1985 to 2016. 

The BetaBank Churn Classification Model project looks at a synthetic dataset of banking customers and performs what is considered by many as the "classic" classification task of data science: predicting churn. Some customers ended their service ("churned") while the rest remain active. The bank has a business interest in developing a model which can predict which users are likely to churn, so that preventative measures such as promotional offers or discounts may be offered.

Below we will be working with a dataset of video game sales for the hypothetical distribution company Ice. Our task is to make conclusions about sales data ranging from 1985 to 2016 to model sales trends for 2017 and beyond. We will begin by sanitizing and organizing the data before doing some preliminary exploratory data analysis. Then we will model active trends for video games released in recent years and conclude with some theories about user score statistics.

The project demonstrates (1) how to preprocess in a  classification model training maximizing f1_score and (2) how to eke out incremental improvements to model performance by balancing class weights and upsampling target samples. It also explores the merits of raising or lowering the threshold for churn risk, which yields different results for the bank. If the bank has a higher threshold, they are more likely to only target users at risk of churning. But too high of a threshold, and users who are lower risk but still end up churning will slip through the cracks.

## Running it Yourself

The Jupyter notebook is self-contained and reflects the outputs of the code contained within. If you would like to connect to your own environment and run the notebook, or make changes on your own fork of the repo, you may do so after cloning. Make sure the environment is either based in the upper-level folder to which you clone the repo, or be sure to replace the dataset file references with a direct local reference to the /datasets/ folder on your machine. 

The project does not require any dependencies and is stable with Python 3.11.