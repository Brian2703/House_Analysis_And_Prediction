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
      ![1](https://github.com/user-attachments/imgs/1.png)
IV. Data Prediction
* ARIMA
* LSTM
* Random Forest
* Gradient Boosting
* Results:

* Based on the evaluation metrics, choosing Gradient Boosting Regression is the most appropriate decision for this project. It achieved the highest R² score of nearly 0.82, which means that the model is able to explain approximately 82% of the variability in house prices — indicating strong predictive power.
* It also recorded the lowest MAE of 210,000, meaning that, on average, the predicted house prices differ from the actual prices by only $210K — a relatively low error given the scale of property prices. Furthermore, the model delivered the lowest MAPE of 13%, showing that the average prediction error is only 13% relative to actual values, making it a highly reliable model for estimating property prices.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/spam-email-classification.git
   cd spam-email-classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook for model training:
   ```bash
   jupyter notebook NSW_House_Price_Analytics_&_Prediction.ipynb
   ```

## License
This project is open-source and available under the MIT License.

## Contributors
- Brian Ong

For any inquiries or contributions, feel free to reach out!

