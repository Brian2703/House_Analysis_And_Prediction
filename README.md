# HOUSING PRICE ANALYSIS AND PREDICTION
The real estate industry remains one of the most attractive sectors for both investors and homebuyers, as owning property - whether as an investment or a family home—is a widely shared aspiration. Domain, one of the leading companies in the real estate market, has experienced significant growth, particularly with property prices climbing dramatically in recent years. Real estate encompasses various property types, including houses, apartments, and vacant land, and its trends often reflect the broader economic conditions of a country. Understanding these shifts is key, and my house price prediction project, focusing on Domain's data, aims to shed light on these developments and forecast future market behavior.

## Project Goal
![Screenshot 2024-11-08 152517](https://github.com/user-attachments/assets/431808bc-71e3-4fe0-ad9f-3c5fd072c30e)
![Screenshot 2024-09-25 001524](https://github.com/user-attachments/assets/d0787d97-d1bf-4a45-82cd-71eb8babf950)

The aim of this Python is to offer an understanding of inquiries;
* What is the trend and future of real estate market;
* What kind of real estate dominate the whole industries;
* What is the average price of properties by segment through years (2016-2021);
* Which suburb is the most attractive with homebuyer and investor based on price per square;
* How the suburb factor impact on housing price (distance from CBD, median income, population and elevation);
* How the property factor impact on housing price (number of bedroom, bathroom, carpark);
* Which areas have the highest concentration of sold properties;
* Is linear regression the most suitable model for predicting house sales, or is there another model that demonstrates greater predictive accuracy;

![Screenshot 2024-11-08 152454](https://github.com/user-attachments/assets/3b9accf9-1d9f-4901-aa80-82cf6f44349f)

## Statistical Method and Machine Learning model
  ![Screenshot 2024-09-25 001553](https://github.com/user-attachments/assets/98137876-6ced-43ae-8776-9775304941b4)

After Cleaning, covert datatype, it is stage for identifying and removing data outlier by 2 main approaches:
* Approach 1: Percentile-based Outlier Removal
* Approach 2: Interquartile Range (IQR) Method for Outlier Detection
Machine Learning Model Using:
* Linear Regression for sales and time series model
* Random Forest
* Adaboost
* Gradient Boosting
Therefore, by using estimated metrics on 4 models, it reveals the best model in this dataset to improve the accuracy rate in house pricing prediction
