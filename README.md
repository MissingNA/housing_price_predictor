# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Predicting Housing Prices with Regression
#### Eu Jin Lee: [GitHub](https://github.com/missingNA)

## Problem Statement

Lee's Estate, a realty firm based in New York is seeking to expand our market around the Midwestern regions of America, specifically in the city of Ames, Iowa. As Ames, Iowa has been ranked the 33th in Best Places to Live. We are interested in exploring the market trends and exploring the pricing of real estate in that region to ensure we stay competitive in our prices.

## Executive Summary
The workflow of the projects is as follows:
    - Importing, cleaning and combining datasets
    - Exploratory data analysis to identify any insights to the nature of the data statistics
    - Modeling 
    - Model Selection 
    - Model Evaluation
    - Conclusions and Recommendations
    
This is a step by step guide in creating a robust model that is able to predict the housing prices based on historical housing data of houses in Ames, Iowa. We use regression techniques, enhanced by feature engineering, feature selection and regularization. 

### Datasets
Datasets used for the project can be found
- [train.csv](https://www.kaggle.com/c/dsi-us-12-project-2-regression-challenge/data?select=train.csv)
- [test.csv](https://www.kaggle.com/c/dsi-us-12-project-2-regression-challenge/data?select=test.csv)

#### Data Dictionary 
For this project, the data dictionary can be accessed [here](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)

---
## Conclusion and Recommendations 

Based on our final model, which performed with a 92.3% accuracy in predicting the variability of the housing dataset that was provided to us. This is good enough in helping us make a confident assessment on the sale prices of house offerring competitive prices within the local market.

Ways we could possibly improve the model further is to incorporate more data into our model such as school data as it is well known that housing prices tend to be affected by the education standards around the area. Furthermore, it is also good to note that the tail end of the timeline of the dataset coincides with the 2010 housing market crash which could possibly have an impact on the results of our model.

## References

-Kaggle Competition Info:
- https://www.kaggle.com/c/dsi-us-12-project-2-regression-challenge/overview

Theory on Handling Missing Data:
- https://towardsdatascience.com/how-to-handle-missing-data-8646b18db0d4

Linear Regression Modeling:
- https://towardsdatascience.com/linear-regression-models-4a3d14b8d368
- https://towardsdatascience.com/regularization-an-important-concept-in-machine-learning-5891628907ea