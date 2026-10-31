Ola Ride Data Analysis (Python & Pandas)

A beginner-friendly data analysis project that cleans a ride-booking dataset and answers common business questions about revenue, ride types, cities, payment modes and customer ratings.

Project Overview

This project simulates the kind of analysis a business or operations team would run on ride-hailing data. Starting from raw ride records, I cleaned the data, handled missing values and duplicates, and then used Pandas to extract insights that support business decisions.

Tools used: Python, Pandas, Jupyter Notebook

Dataset

A sample dataset of ride records created in the notebook (11 raw rows, 9 after cleaning).

Column	Description
Ride_ID	Unique ride identifier
Customer_Name / Driver_Name	Customer and driver for the ride
City	Satara, Pune, Mumbai, Nashik, Sangli, Kolhapur
Ride_Type	Mini, Prime, Auto
Distance_KM	Trip distance
Fare	Fare charged (INR)
Payment_Mode	UPI, Cash, Card
Rating	Customer rating (out of 5)
Ride_Status	Completed / Cancelled
What I Did
Created and stored the data – built a DataFrame and saved/loaded it as a CSV file.
Explored the data – used head(), tail(), shape, columns, and describe() to understand structure and statistics.
Cleaned the data
Detected missing values with isnull()
Removed duplicate records (drop_duplicates())
Removed incomplete records
Filled missing ratings with the average rating
Analyzed the data – used filtering, sorting, and group-by analysis to answer business questions.
Key Findings
Metric	Result
Total rides analysed	9
Total revenue	₹2,990
Average fare	₹332
Highest / lowest fare	₹700 / ₹100
Revenue from completed rides	₹1,800
Completed vs. cancelled rides	62.5% vs. 37.5%
Most used payment mode	UPI

Insights

Top cities by revenue: Satara (₹950), Mumbai (₹770), Pune (₹600).
Prime rides earn the most per trip (avg ₹617) and have the best ratings (avg 4.9), compared with Mini (₹263, 4.4) and Auto (₹123, 3.97).
Payment modes are evenly split by revenue: Card ₹1,000, UPI ₹1,000, Cash ₹990.
Top drivers by revenue: Sameer (₹700), Rohit (₹650), Akash (₹500).
Cancellations are high (about 3 in 8 rides with a known status), which is an area worth investigating.
Business Questions Answered
How many rides were there, and what was the total and average revenue?
Which city, ride type and driver generate the most revenue?
What is the average rating and fare by ride type?
Which payment mode is used most?
What share of rides were completed vs. cancelled?
Which rides have fares above ₹500 and ratings above 4?
Skills Demonstrated
Data cleaning (missing values, duplicates, filtering)
Exploratory data analysis (EDA)
Aggregation and group-by analysis
Turning raw data into business insights
Clear documentation of work in a Jupyter Notebook
Limitations

This is a small sample dataset (9 clean rows), so results are for practice and demonstration, not for drawing real-world conclusions about Ola.

How to Run
bash
pip install pandas jupyter
jupyter notebook Olaproject.ipynb
