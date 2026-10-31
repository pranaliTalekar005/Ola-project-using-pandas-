🚖 Ola Ride Data Analysis (Python & Pandas)



 Project Overview

This is a beginner-friendly Data Analysis project using Python and Pandas.

The main objective of this project is to analyze Ola ride-booking data and identify useful business insights related to revenue, ride types, cities, payment modes, customer ratings, and ride status.

The project starts with raw ride records, followed by data cleaning, data exploration, and exploratory data analysis (EDA).

 🛠️ Tools & Technologies

- Python
- Pandas
- Jupyter Notebook

📂 Dataset Description

The project uses a sample dataset containing 11 raw ride records, which were reduced to 9 records after data cleaning.

| Column Name | Description |
|---|---|
| Ride_ID | Unique ride identifier |
| Customer_Name | Customer name |
| Driver_Name | Driver name |
| City | Ride location |
| Ride_Type | Mini, Prime, Auto |
| Distance_KM | Trip distance |
| Fare | Fare charged (INR) |
| Payment_Mode | UPI, Cash, Card |
| Rating | Customer rating out of 5 |
| Ride_Status | Completed / Cancelled |

🔄 Project Workflow
1. Data Creation
- Created a DataFrame using Pandas.
- Stored the dataset in CSV format.
- Loaded the CSV file into Jupyter Notebook.

2. Data Exploration
Used the following functions to understand the dataset:

- `head()`
- `tail()`
- `shape`
- `columns`
- `describe()`

3. Data Cleaning
- Identified missing values using `isnull()`.
- Removed duplicate records using `drop_duplicates()`.
- Removed incomplete records.
- Filled missing ratings using the average rating.

4. Exploratory Data Analysis (EDA)
- Applied filtering and sorting.
- Performed group-by analysis.
- Calculated total and average revenue.
- Compared ride types, cities, drivers, and payment modes.

 📊 Key Performance Indicators (KPIs)

| Metric | Result |
|---|---:|
| Total Rides Analysed | 9 |
| Total Revenue | ₹2,990 |
| Average Fare | ₹332 |
| Highest Fare | ₹700 |
| Lowest Fare | ₹100 |
| Completed Rides Revenue | ₹1,800 |
| Completed Rides | 62.5% |
| Cancelled Rides | 37.5% |
| Most Used Payment Mode | UPI |

 💡 Key Business Insights

### 🏙️ City-wise Revenue
Top cities based on revenue:

| City | Revenue |
|---|---:|
| Satara | ₹950 |
| Mumbai | ₹770 |
| Pune | ₹600 |

**Insight:** Satara generates the highest revenue among the listed cities.

🚘 Ride Type Analysis

| Ride Type | Average Fare | Average Rating |
|---|---:|---:|
| Prime | ₹617 | 4.9 |
| Mini | ₹263 | 4.4 |
| Auto | ₹123 | 3.97 |

**Insight:** Prime rides generate the highest average fare and have the best customer ratings.

💳 Payment Mode Analysis

| Payment Mode | Revenue |
|---|---:|
| Card | ₹1,000 |
| UPI | ₹1,000 |
| Cash | ₹990 |

**Insight:** Revenue is almost equally distributed across all three payment modes.

### 👨‍✈️ Driver-wise Revenue

| Driver | Revenue |
|---|---:|
| Sameer | ₹700 |
| Rohit | ₹650 |
| Akash | ₹500 |

**Insight:** Sameer generates the highest revenue among the listed drivers.

❌ Ride Cancellation Analysis

Approximately 3 out of 8 rides with a known status were cancelled.

**Insight:** The cancellation rate indicates an opportunity to investigate the reasons behind ride cancellations and improve operational efficiency.

❓ Business Questions Answered

1. How many rides were recorded?
2. What is the total and average revenue?
3. Which city generates the highest revenue?
4. Which ride type generates the highest average fare?
5. Which driver generates the highest revenue?
6. What is the average rating by ride type?
7. Which payment mode is used most?
8. What is the percentage of completed and cancelled rides?
9. Which rides have fares above ₹500 and ratings above 4?

🎯 Skills Demonstrated

- Data Cleaning
- Data Manipulation using Pandas
- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Duplicate Removal
- Filtering and Sorting
- GroupBy and Aggregation
- Business Insights Generation
- Jupyter Notebook Documentation

⚠️ Project Limitations

This project uses a small sample dataset containing only 9 cleaned records.

Therefore, the findings are intended for learning and demonstration purposes and should not be considered actual Ola business results.

## 🚀 How to Run This Project

**Step 1:** Install the required libraries.

```bash
pip install pandas jupyter
```

**Step 2:** Start Jupyter Notebook.

```bash
jupyter notebook
```

**Step 3:** Open the project notebook and run the cells.

## 👩‍💻 Author

**Pranali Talekar**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

