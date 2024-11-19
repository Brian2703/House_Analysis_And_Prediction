# HOUSING PRICE ANALYSIS AND PREDICTION
The real estate industry remains one of the most attractive sectors for both investors and homebuyers, as owning property - whether as an investment or a family home—is a widely shared aspiration. Domain, one of the leading companies in the real estate market, has experienced significant growth, particularly with property prices climbing dramatically in recent years. Real estate encompasses various property types, including houses, apartments, and vacant land, and its trends often reflect the broader economic conditions of a country. Understanding these shifts is key, and my house price prediction project, focusing on Domain's data, aims to shed light on these developments and forecast future market behavior.

## Project Outline
I. Introduction
  1. Overview Of Project
  2. Objective and Define problem
II. Data Collection and Preprocessing
  1. Data Source
  2. Data Loading
  3. Data Dictionary
III. Exploratory Data Analysis (EDA)
  1. Summary Statistics
  2. Data Cleaning and Datatype Modification
     * Identify Duplicate and Handle Missing data
     * Data Convertion
     * Outlier Detection and Removal
  3. Data Analysis and Visualization
     * Overview of Domain Performance (2016-2021)
      ![Screenshot 2024-11-19 134824](https://github.com/user-attachments/assets/72911f0a-7efc-4feb-973d-9544651a4108)
      Generally, houses have dominated the real estate market since 2016 in the Domain     dataset, making up 88.7% of the company’s revenue. Apartments account for 4.5% of total sales, vacant land for 1%, and other types of housing, such as semi-attached houses and studios, for 5.8%.
      ![Screenshot 2024-11-19 134926](https://github.com/user-attachments/assets/47f8ce8a-c553-4b0a-86ee-8d030a800f15)
      The real estate industry experienced a quiet period starting in 2016, with three house types reaching their lowest points in five years. Then, it began to recover in Q2 2020 after a dramatic drop in Q1 2019 due to the pandemic’s impact. By the last quarter of 2021, every house type had hit its peak, particularly, 4.4 Billion for house, 173 Million dollars for Apartment and almost 30 Million dollars for vacant land.
      ![Screenshot 2024-11-19 135055](https://github.com/user-attachments/assets/c393e19c-7c7f-4f82-ab2d-42566e8aad97)
      ![Screenshot 2024-11-19 135107](https://github.com/user-attachments/assets/492e054a-734f-4578-951f-0ed58151eb0d)
      By looking at the chart, we can see that real estate transactions have dramatically increased recently, especially since 2021. Every house type has seen a significant rise, hitting a peak in the last quarter of 2021. This can be explained by the impact of the pandemic in 2019 and 2020. After that quiet period, the real estate market recovered strongly compared to 2019 and earlier.

     * Average Price of Properties by Segment through years
      ![Screenshot 2024-11-19 135222](https://github.com/user-attachments/assets/f612288e-cd04-40d0-a2ce-365d5ef41677)
     We can clearly see that the average prices of houses and apartments remained stable and slightly decreased from 2016 to 2018. Especially for apartments, the price dramatically went down to 0.89M in 2019, while house prices reached 1.4M that year. After 2019, both prices increased, reaching 2.04M for houses and 1.5M for apartments in 2021.
Additionally, vacant land is the most volatile segment in the real estate industry. After declining from 2017 to 2019, its price rose until 2021. This can be explained in two ways: either the real price of vacant land is increasing, or the recent transactions of vacant land are too few but involve larger amounts of money. However, in this dataset, we don’t have enough data about vacant land to draw a definitive conclusion.

     * Suburb Housing Price Overview
      ![Screenshot 2024-11-19 135350](https://github.com/user-attachments/assets/8f70993a-dd67-48c1-b3e9-1cfe48f129e7)
    *  Feature Relationship
       * The relationship between housing price with suburb elevation
       * The relationship between housing price with Distance from CBD
       * The relationship between housing price and suburb's feature (Population & Income)
       * Housing Price and Properties's Conviniences Analysis
       ![Screenshot 2024-11-19 135421](https://github.com/user-attachments/assets/44f8e566-dbff-4600-8683-7615e3f15fd8)
       ![Screenshot 2024-11-19 135405](https://github.com/user-attachments/assets/994cdc02-3403-45d6-a2cc-a55ed798271c)
       ![Screenshot 2024-11-19 135838](https://github.com/user-attachments/assets/2edd6fdd-71af-479a-85e1-43074f88a96c)
       ![Screenshot 2024-11-19 135824](https://github.com/user-attachments/assets/a7dafd22-ac06-4140-a337-d8ad4c757e1c)
    *  Map Analysis
IV. Data Prediction
* ARIMA
* LSTM
      ![Screenshot 2024-11-19 140322](https://github.com/user-attachments/assets/367a7bb7-4fe8-4573-87d7-c431f3a940bc)
* Random Forest
* Adaboost
* Gradient Boosting
* Results:
Gradient Boosting with the score at 86.91%, which is higher than the rest in Sales prediction


Therefore, by using estimated metrics on 6 models, it reveals the best model in this dataset to improve the accuracy rate in house pricing prediction
