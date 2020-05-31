# Predicting NYC Housing Prices
Spring 2019 Business Analytics Club Project 

## Introduction:
New York City is notoriously known for its expensive real estate market. Across the different boroughs you see a lot of diversity in in NYC is very diverse across the different boroughs and very dynamic from year to year. Our data is 166,968 properties from the NYC Department of Finance’s records that were sold in New York City from September 2016 to December 2018.

## Datasets: 
https://www.kaggle.com/new-york-city/nyc-property-sales
https://www1.nyc.gov/site/finance/taxes/property-rolling-sales-data.page

## Goal:
1. Perform various regression analyses to predict housing prices 
2. Identify factors that are most important to determining price
3. Learn Python packages and modeling techniques

## Timeline:
March 8, 15: Exploratory Analysis
* Deliverables: Tableau Visualizations, Correlations, Variable Distributions

March 22, 29: Classification Building
* Deliverables: Linear Regression, Random Forest Regression, Analyze Findings

April 5: Explore More Complex Models
* Deliverables: Ridge Regression, ElasticNet?, Neural Net, etc.
* Troubleshooting: nested regression model to impute missing square footage values

April 12, 19: Model Refinement and Interpretation
* Deliverables: Gridsearch, Visualizations of Learning Curves, ROC, Accuracy

April 26: Finalize
* Deliverables: Final Predictive Ability

May 3: Practice Presentation
* Deliverables: [Slide deck](Housing Price Prediction.pdf)

## Conclusion
Our analysis scan serve as a tool for real estate investors and homeowners to check property valuations. This is important in:
* Ensuring accurate property tax and asset management 
* Identifying good deals for primary residence or investment purchases

**Best Model:** 83.86% hold out accuracy on Random Forest Regressor with max depth of 15 and 20 estimators. 
