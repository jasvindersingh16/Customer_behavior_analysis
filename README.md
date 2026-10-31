# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project focuses on analyzing customer shopping behavior to identify purchasing patterns, customer preferences, and business insights.

The project follows an end-to-end data analytics workflow, starting with data exploration and cleaning in Python, followed by SQL-based analysis using MySQL, and finally creating an interactive dashboard in Power BI.

The objective is to transform raw customer shopping data into meaningful insights that can support better business decisions.

## 📂 Dataset

- **Dataset:** Customer Shopping Behavior Dataset
- **Total Records:** 3,900
- **Domain:** Retail / E-commerce
- **Data Includes:** Customer demographics, product categories, purchase amounts, discounts, reviews, shipping preferences, and subscription information.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data cleaning and manipulation |
| Matplotlib / Seaborn | Exploratory Data Analysis (EDA) |
| MySQL | SQL queries and business analysis |
| Power BI | Interactive dashboard development |
| Gamma | PowerPoint presentation |
| Jupyter Notebook / Google Colab | Python environment |

## 🔄 Project Workflow

### 1. Data Loading & Exploration (Python)
- Imported the dataset using Pandas.
- Explored the dataset structure, columns, and data types.
- Analyzed missing values and duplicate records.
- Performed Exploratory Data Analysis (EDA) to understand customer purchasing patterns.

### 2. Data Cleaning & Preprocessing
- Handled missing and inconsistent values.
- Checked and removed duplicate records where necessary.
- Standardized column names and data formats.
- Prepared the cleaned dataset for SQL analysis.

### 3. SQL Analysis (MySQL)
- Imported the cleaned dataset into MySQL.
- Used SQL queries to answer business-related questions.
- Analyzed customer segments, product performance, revenue, and discount usage.
- Used aggregate functions, GROUP BY, JOINs, subqueries, and window functions where required.

### 4. Power BI Dashboard
- Connected Power BI to the cleaned dataset.
- Created interactive visualizations and KPI cards.
- Added slicers to explore customer behavior across different categories.
- Designed a dashboard to present key business metrics and trends.

### 5. Reporting & Presentation
- Prepared a project report summarizing the analysis and findings.
- Created a PowerPoint presentation using Gamma.
- Presented the project workflow, key insights, and business recommendations.

## 📊 Dashboard

The Power BI dashboard provides an interactive view of customer shopping behavior.

**Key metrics and visualizations include:**
- Total number of customers
- Average purchase amount
- Average customer review rating
- Customer subscription status
- Revenue by product category
- Revenue by age group
- Sales distribution across age groups

<!-- Add your Power BI dashboard screenshot here -->
![Customer Behavior Dashboard](images/customer_behavior_dashboard.png)

## 📈 Results & Key Learnings

This project helped explore customer purchasing behavior and understand how data analytics can support retail business decisions.

Key areas of analysis included:

- Understanding customer demographics and purchasing patterns.
- Identifying product categories and customer segments.
- Analyzing discount usage and subscription behavior.
- Comparing revenue and sales across different age groups.
- Presenting analytical findings through an interactive dashboard.

**Key Learning Outcomes:**
- Hands-on experience with Python and Pandas for data cleaning.
- Practical SQL querying and business analysis using MySQL.
- Building interactive dashboards using Power BI.
- Understanding the complete data analytics workflow, from raw data to business insights.

## 🚀 How to Run the Project

### Prerequisites
Install the following tools:
- Python 3.x
- Jupyter Notebook or Google Colab
- MySQL Server and MySQL Workbench
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### Step 2: Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 3: Run Python Analysis
- Open the Python notebook.
- Load the original dataset.
- Execute the EDA and data-cleaning steps.
- Export the cleaned dataset as a CSV file.

### Step 4: Perform SQL Analysis
- Start your MySQL Server.
- Create a database.
- Import the cleaned CSV file into MySQL.
- Open and execute the SQL script provided in the repository.

### Step 5: Open the Power BI Dashboard
- Open the `.pbix` file using Power BI Desktop.
- Connect or update the data source if required.
- Refresh the dataset to view the dashboard.

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   ├── customer_shopping.csv
│   └── customer_shopping_cleaned.csv
│
├── Python/
│   └── customer_shopping_analysis.ipynb
│
├── SQL/
│   └── customer_shopping_analysis.sql
│
├── PowerBI/
│   └── customer_behavior_dashboard.pbix
│
├── Report/
│   └── project_report.pdf
│
├── Presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── customer_behavior_dashboard.png
│
└── README.md
```

*Note: Update the folder and file names above to match your actual GitHub repository.*

## 👨‍💻 Author

**Jasvinder Singh**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

This project demonstrates my practical understanding of data cleaning, exploratory data analysis, SQL querying, data visualization, and business reporting.

Feel free to explore the repository and share your feedback!
