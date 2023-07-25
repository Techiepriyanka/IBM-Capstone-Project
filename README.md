# IBM-Capstone-Project
This project is surrounded around complex Airbnb Dataset in which I have performed Exploratory Data Analysis (EDA) using python. 

A brief overview of the implementation of my Capstone project which is a part of the IBMs Data Analytics Specialization programme.

##Overview

- I performed Data Analytics on Airbnb data using Python.
- I Gained insights, cleaned the data, transformed it, and also visualized key information.
- I improved Airbnb's services and understood market trends.

## Dataset Source

- I accessed the dataset from [Airbnb Open Data](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata).
- It Contains information on neighborhoods, room types, prices, availability, reviews, service fees, etc.

## Steps in Python Implementation

1. **Data Loading (Python)**:
   -I  read the CSV file and loaded it into a pandas DataFrame.
   - I displayed the first five rows of the DataFrame.
   - I also displayed the data types of the columns.

2. **Data Cleaning (Python)**:
   - I dropped unwanted columns (e.g., host ID, ID, country, country code).
   - I checked for missing values, impute based on data type.
   - I checked for duplicates as well as eliminated it if present in the 
     dataset.
   - I displayed total number of records before and after removing 
    duplicates.

3. **Data Transformation (Python)**:
   - I renamed "availability 365" to "days_booked."
   - I converted column names to lowercase and replace spaces with 
     underscores.
   - I removed dollar sign and comma from "price" and "service_fee," if 
     necessary.
   - I converted these columns to appropriate data types.

4. **Exploratory Data Analysis (Python)**:
   - I listed count of various room types available.
   - Also Determined room type with the most strict cancellation 
     policy.
   -I listed average price per neighborhood group, highlighted the most expensive neighborhood.

5. **Data Visualization (Python)**:
   - I created horizontal bar chart for the top 10 most expensive neighborhoods.
   -I created another chart for the 10 cheapest neighborhoods.
   - I created a box and whisker chart for price distribution of listings by room type.
   - I created a scatter plot to show the relationship between cleaning fee and room price.
   -I created a line chart for the total number of listings available per year.
   - I created a data visualization of choice using review columns.
   - Compared variables between super hosts and regular hosts using visualizations.

## Conclusion

In this capstone project, I used Python to perform Data Analytics on Airbnb data. I gained insights, cleaned the data, transformed it, and created visualizations to better understand Airbnb's services and market trends. By completing this project, have improved your Python skills and acquired valuable experience in real-world data analysis. 
