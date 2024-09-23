
# Retail Order Sales Insight 
 ## ETL (Python + SQL + Power BI)

This dataset contains sales information of retail orders from a store. In this project, I extract sales insights from the dataset, such as total revenue, profit margin, which country contributes the most to revenue, and which contributes the most to profit margin, along with other useful insights.

# Approach
I am using the ETL (Extract, Transform, Load) methodology for this dataset, which means first we will extract the dataset, transform it into a usable format, and then load the data into an appropriate database to find insights.

**1. Extract:**
I used Python for extracting the dataset from Kaggle, and for that, I used the Kaggle API to download the dataset.
After downloading the dataset, I used Pandas to import the data into a dataframe.

**2. Transform:**
After importing the data, the next step is to clean it.
Cleaning the data involves checking columns, changing some column names and their data types if required, checking for duplicate values and removing them if found, replacing some unwanted values with null values, replacing null values with mean, median, and mode for numerical and categorical data respectively, removing some unwanted columns, and adding some necessary columns, etc.

**3. Load:**
After transforming the data, I loaded the dataset into a MySQL database using SQLAlchemy, MySQL Connector, and Pandas libraries.
In MySQL, I found some sales insights, such as which are the top revenue-generating products, the highest-selling products by region, sales comparisons by each month and year, etc.

Finally, I created an interactive Power BI dashboard for easy understanding of the insights by stakeholders.

# Key Findings:
- In terms of revenue, the business is performing well, but the profit margin situation is concerning.
- Revenue increased from 2022 to 2023, but the profit margin decreased.
- The top revenue-contributing states are California, New York, and Washington, respectively.
- The Corporate segment contributes the most to revenue.
- The East region contributes the most to profit, and the Chairs sub-category contributes the most to profit margin.

# Tool Used:
- Python and Kaggle API for extracting data
- Pandas for data cleaning and transformation
- Advanced SQL queries
- Power BI DAX queries










