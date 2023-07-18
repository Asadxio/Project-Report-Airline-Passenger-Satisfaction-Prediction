# Project-Report-Airline-Passenger-Satisfaction-Prediction

# Project Report: Airline Passenger Satisfaction Prediction

## Introduction

The objective of this project is to predict airline passenger satisfaction using random forest, gradient boosting, and K-nearest neighbors (KNN) algorithms. The project utilizes the airline passenger satisfaction dataset available on Kaggle, which provides information about various factors influencing passenger satisfaction.

Dataset: [Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/mysarahmadbhat/airline-passenger-satisfaction?resource=download)

The dataset includes the following variables:

1. **ID**: Unique passenger identifier
2. **Gender**: Gender of the passenger (Female/Male)
3. **Age**: Age of the passenger
4. **Customer Type**: Type of airline customer (First-time/Returning)
5. **Type of Travel**: Purpose of the flight (Business/Personal)
6. **Class**: Travel class in the airplane for the passenger seat
7. **Flight Distance**: Flight distance in miles
8. **Departure & Arrival Delay**: Flight departure & arrival delay in minutes
9. **Satisfaction**: Overall satisfaction level with the airline (Satisfied/Neutral or unsatisfied) *(Satisfaction level ranges from 1 (lowest) to 5 (highest), 0 means "not applicable")*
10. **Departure & Arrival Time Convenience**
11. **Ease of Online Booking**
12. **Check-in Service**
13. **Online Boarding**
14. **Gate Location**
15. **On-board Service**
16. **Seat Comfort**
17. **Leg Room Service**
18. **Cleanliness**
19. **Food and Drink**
20. **In-flight Service**
21. **In-flight Wifi Service**
22. **In-flight Entertainment**
23. **Baggage Handling**

## Project Steps

1. Import Libraries: The necessary libraries and modules are imported to support the project's implementation.

2. Load Dataset: The dataset is loaded from the provided CSV file and stored in a Pandas DataFrame for further analysis.

3. Data Understanding: Various aspects of the dataset are explored to gain an understanding of its contents and structure. This includes checking the data description, examining the data info, and identifying any missing values.

4. Data Preparation: The necessary steps are taken to prepare the dataset for analysis. This includes handling missing values and identifying and removing any duplicated data.

5. Statistical Summary: A statistical summary of the dataset is presented, including descriptive statistics for numerical columns and summary statistics for categorical columns.

6. Outlier Detection: Outliers in the dataset are detected and visualized using boxplots.

7. Encoding Categorical Columns: Categorical columns are encoded to numerical representations for further analysis. One-hot encoding is used for selected columns, while label encoding is applied to the target column.

8. Export Encoded Data for EDA: The encoded dataset is exported as a CSV file for exploratory data analysis (EDA) purposes.

## Conclusion

In this project, we explored the airline passenger satisfaction dataset and performed various data preparation and analysis steps. We encoded categorical columns, handled missing values, and detected outliers in the dataset. The encoded dataset was exported for further analysis, such as EDA and building predictive models for airline passenger satisfaction.

The project provides a foundation for predicting and understanding passenger satisfaction, which can have implications for improving the overall customer experience in the airline industry.

