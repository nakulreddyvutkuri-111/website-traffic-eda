# Website Traffic EDA & Business Intelligence

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) and Business Intelligence on a website traffic dataset using Python, SQL, and Kaggle.

The objective of this project is to uncover trends, patterns, and user behavior insights from website traffic data through data analysis, visualization, and SQL-based business queries.

---

## Objectives
- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Analyze user traffic trends and patterns
- Answer business-related questions using SQL
- Create visualizations for better insights
- Propose KPI dashboard metrics

---

## Dataset Information
The dataset contains website traffic event details including:

- Event Type
- Date
- Country
- City
- Artist
- Album
- Track
- ISRC Code
- Link ID

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- SQLite
- Kaggle Notebook

---

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas
- Explored rows, columns, and dataset structure

### 2. Data Cleaning
- Removed duplicate rows
- Handled missing values
- Converted date columns into datetime format

### 3. Exploratory Data Analysis (EDA)
Performed:
- Descriptive statistics
- Event analysis
- Country-wise traffic analysis
- Artist popularity analysis
- Time-series traffic trend analysis

### 4. Data Visualization
Created charts including:
- Bar charts
- Traffic trend plots
- Country vs Event analysis

### 5. SQL Business Queries
Executed SQL queries to answer business questions such as:
- Top countries generating traffic
- Most popular artists
- Most common event types
- Top traffic-generating cities

### 6. KPI Dashboard Planning
Identified key business KPIs:
- Total Website Events
- Top Countries
- Daily Traffic
- Most Active Artists
- Event Distribution

---

## Key Insights
- Certain countries generated significantly higher website traffic.
- User engagement varied across different event types.
- Popular artists contributed to higher traffic interactions.
- Traffic trends changed over time, showing user activity patterns.

---

## Output Files
- EDA Notebook
- Cleaned Dataset (`eda_cleaned_traffic.csv`)
- SQL Query Results
- Visualizations

---

## Sample SQL Query

```sql
SELECT country, COUNT(*) as total
FROM traffic_data
GROUP BY country
ORDER BY total DESC
LIMIT 10;
```

---

## Conclusion
The project successfully demonstrated the use of EDA and SQL for extracting business insights from website traffic data. Through visualizations and analytical techniques, meaningful patterns and trends were identified to support data-driven decision-making.

---

## Author
Nakul Reddy Vutkuri
