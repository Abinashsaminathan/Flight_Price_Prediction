# Flight Ticket Price Prediction

## Business Problem Statement

The objective of this project is to accurately predict the prices of flight tickets. This prediction can benefit both airlines and passengers by providing insights into ticket pricing trends.

## Data Science Approach

This project follows a supervised learning approach, specifically regression, as historical flight data with labeled ticket prices is available for training the model.

## Data Features / Independent Variables

- `Flight_ID`: Identifier for each flight.
- `Airline`: The airline associated with the flight (categorical).
- `Departure_City`: The city where the flight departs from.
- ...

## Tech Stack

- Python
- SQL/MongoDB
- Machine Learning (Sklearn)
- Mathematics (Numpy)
- Visualization (Plotly)
- Statistics

## Machine Learning Model - End to End

### Requirements

Make sure you have the necessary packages and their versions installed.

### Get the Data

Retrieve the flight ticket price dataset from the source.

### Exploratory Data Analysis (EDA)

Perform exploratory data analysis using Pandas to understand the dataset:

- Display the first few rows.
- ...

### Data Visualization (Using SweetViz)

Create various visualizations to understand data patterns, relationships, and trends.

### Data Preprocessing

- Split the data into training, validation, and test sets to prevent data leakage.
- Handle missing values and outliers.
- ...

### Data Encoding

Encode categorical features using techniques like one-hot encoding or label encoding. Scale numerical features using standard scaling.

### Machine Learning Model Selection

Choose an appropriate machine learning model. In this case, XGBoost is selected for regression.

### Model Training and Evaluation

Train the selected model using the training dataset. Evaluate the model's performance using metrics such as Root Mean Squared Error (RMSE).

## Conclusion

The model's RMSE score is 12.5, indicating the accuracy of flight ticket price predictions.

---

This README provides an overview of the project, including its purpose, approach, tech stack, and the steps involved in the end-to-end process. It also serves as a guide for anyone interested in understanding and replicating the project.

