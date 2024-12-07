# Predicting Car Categories and Purchase Prices: A Machine Learning Approach to Consumer Behavior Analysis

## Project Overview

In 2023, approximately 1.76 million cars were sold in Canada, marking a 12.9% increase (year-over-year). Therefore, understanding customer preferences and spending behavior could give dealerships an edge in remaining competitive and capturing some of the revenue these growing sales are generating. This project aims to classify potential purchases into various car categories (e.g., SUV, Hatchback) by leveraging customer data like age, income, gender and previous vehicle purchased. These insights will enable businesses to tailor their marketing strategies effectively.

The question this project aims to address is:

#### Which car category (e.g., SUV vs sedan) a customer is likely to purchase based on demographic factors and historical purchase data?

## Team Members (GitHub Username) - Video

- Aadil Shaikh ([aadil-shaikh786](https://github.com/aadil-shaikh786)) - Video Explaination
- Felipe Bastos ([fbastos231](https://github.com/fbastos231)) - Video Explaination
- Shayan Hodai ([ShayanHodai](https://github.com/ShayanHodai)) - Video Explaination
- Si Jiao Liu ([sijiao-liu](https://github.com/sijiao-liu)) - Video Explaination
- Xuan (Heather) Wu ([lookatme818](https://github.com/lookatme818)) - Video Explaination


## Dataset

The dataset for this project is from Kaggle: [Car Sales Report Dataset](https://www.kaggle.com/datasets/missionjee/car-sales-report). It provides comprehensive data on automotive sales transactions, including customer demographics, dealer information, and vehicle specifics. Below is a detailed breakdown of the collected data and its relevance to our research objectives.

#### Attributes of the Dataset
The dataset contains the following key columns, each representing important information related to car sales:

| Variable Name     | Data Type | Description                                                   |
|-------------------|-----------|---------------------------------------------------------------|
| `Car_id`          | String    | Unique identifier for each car in the dataset.               |
| `Date`            | Datetime  | The date of the transaction (format: MM/DD/YYYY).            |
| `Customer Name`   | String    | Name of the customer who purchased the vehicle.              |
| `Gender`          | String    | Gender of the customer (e.g., Male).                         |
| `Annual Income`   | Integer   | Annual income of the customer (in local currency).           |
| `Dealer_Name`     | String    | Name of the car dealership where the sale was made.          |
| `Company`         | String    | Manufacturer or company of the car (e.g., Ford, Cadillac).   |
| `Model`           | String    | The specific model of the car sold (e.g., Expedition).       |
| `Engine`          | String    | Type of engine (e.g., Overhead Camshaft).                    |
| `Transmission`    | String    | Type of transmission (e.g., Auto, Manual).                   |
| `Color`           | String    | The color of the vehicle sold (e.g., Black, Red).            |
| `Price ($)`       | Integer   | Price of the car in dollars.                                 |
| `Dealer_No`       | String    | Unique identifier for the dealership.                        |
| `Body Style`      | String    | The body style of the vehicle (e.g., SUV, Hatchback).        |
| `Phone`           | String    | Phone number associated with the dealership.                 |
| `Dealer_Region`   | String    | Geographical region of the dealership (e.g., Middletown).    |


#### Full code available here: 
[https://github.com/sijiao-liu/customer-car-prediction/Classification Model - fbastos.ipynb](https://github.com/sijiao-liu/customer-car-prediction/blob/e1fe0cf53164f5773a52b790a00428914b48add7/code/Classification%20Model%20-%20fbastos.ipynb)

#### Code requirements are available here:

## Models Evaluated

## Final Model & Results

![confusion matrix.png](./image/confusion_matrix.png)

## Conclusion

CONCLUSION TO BE ADDED

## Future Work

Improvements to classification model:

- Add validation split as well (75% training, 10% validation, 15% testing)
- Add ROC/AUC curves & Metrics progression chart (Bar char of bar charts)


Using a regression model to to predict customer spending Behavior based on Income, Gender, and Region:

- This part of the project would aim at developing a regression model to predict how much a customer is likely to spend on a vehicle. It analyzes key features such as income, gender, region, and other socio-economic variables to model the spending patterns of car buyers.

## References

https://www.consumeraffairs.com/automotive/how-big-is-the-automotive-industry.html#key-insights

https://www.statista.com/statistics/423012/motor-vehicle-sales-in-canada/#:~:text=Canadian%20motorists%20purchased%20around%201.76%20million%20new%20motor%20vehicles%20in%202023.