# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to create, analyze and compare models for estimating credit risks of different consumers. Over the course of this analysis, we have greated several regressions to compare for accuracy and variation of potential predictions. Through comparing these different regressions, we can better model the outcome of the data by finding the model of best fit. 

## Balanced Accuracy Score Results

When analyzing the balanced accuracy scores of each of our regression analysis, we will find that the Balanced Random Forest classifier method gives us the highest accuracy score (78% accuracy) , followed by naive oversampling (65% accuracy) (which only differs from our SMOTE method by less than a %) and the least accurate being undersampling (53%). 

## Precision Score Results

Our most precise model was created using our SMOTEEN analysis method. The results of this are demonstrated below (61 observations were predicted true and proved to in fact be true):

<img width="442" alt="Screen Shot 2022-07-03 at 9 44 52 PM" src="https://user-images.githubusercontent.com/99772755/177067519-22e11f61-6031-43fc-aac7-a148e68ed22f.png">

Following in second with 55 precise estimates proving to be true is our SMOTE oversampling approach:

<img width="311" alt="Screen Shot 2022-07-03 at 9 44 40 PM" src="https://user-images.githubusercontent.com/99772755/177067599-ab453126-9966-40c6-8e0c-b584637f14df.png">

## Model Recommendation

Based on the above explained analysis, I believe it would be best to use the SMOTE oversampling method as our model, as it consistently proves to rank in the top 2 most accurate. Although other samples test stronger, they are not consistently stronger leading to concern surrounding their all around level of accuracy.
