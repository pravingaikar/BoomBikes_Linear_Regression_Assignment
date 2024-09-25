# Project Name
> BoomBikes Demand Estimation with Linear Regression.


## Table of Contents
* [General Info](#general-information)
* [Contact](#contact)
* [Conclusion](#Conclusion)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project focuses on building a multiple linear regression model to predict the demand for BoomBikes bike rentals. It was completed as part of the coursework in the Machine Learning module of the Executive PG program in Machine Learning and AI from IIIT Bangalore.

### Background:
BoomBikes, a bike-sharing service provider in the US, experienced a significant revenue drop during the COVID-19 pandemic. To recover and prepare for the post-pandemic market, the company seeks to understand the key factors affecting bike rental demand.

### Business Problem:
The primary business problem is predicting the demand for shared bikes based on external factors such as weather, temperature, humidity, holidays, and other conditions. Understanding these factors will help BoomBikes optimize their service offerings and align their business strategy to meet customer needs.

### Dataset:
The dataset used for this project is the BoomBikes bike rental dataset. It contains daily data on bike rentals across various American cities, along with associated factors such as weather, temperature, and holidays.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusion
The model's performance after data interpretation, visualization, preparation, model building, training, residual analysis, and evaluation of the test data is summarized as follows:

    The R-squared value is 82.9% for the training set and 80.03% for the test set, indicating that the model explains a significant portion of the variance in the test set. This suggests that the model is reliable and performs well.

    The model's mean squared error is close to zero for both the training and testing datasets, demonstrating that it accurately predicts the variance in the test set. Significant variables were selected using p-values and Variance Inflation Factor (VIF), and Recursive Feature Elimination (RFE) was used for automated variable selection.

    The analysis shows that bike demand for BoomBikes is influenced by temperature and whether it is a working day. Higher rental demand is observed in winter compared to summer and spring. September and October see increased rentals, particularly on days like Wednesday, Thursday, and Saturday, and during holidays.

    These insights provide valuable understanding of the bike rental market and consumer behavior. One recommendation based on the model is to focus on aggressive marketing during summer and spring to boost rentals. Since rental demand is lower during these seasons, a robust marketing strategy in the first half of the year can help increase rental numbers. Additionally, efforts should be made to attract users on days with less favorable weather, possibly through incentives or strategic promotions. The increase in rentals from 2018 to 2019 suggests growing interest in the service, highlighting the need for targeted strategies to retain repeat customers.


## Contact
Created by [@pravingaikar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->