# Customer Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior to identify purchasing patterns, customer segments, and factors influencing purchase activity.

The data was cleaned and transformed using Python, stored in PostgreSQL, and prepared for analysis and visualization.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- PostgreSQL
- SQLAlchemy
- SQL
- Power BI

## 🔄 Project Workflow

1. Loaded the customer shopping dataset using Python.
2. Cleaned and standardized column names.
3. Created age groups using customer age.
4. Converted purchase frequency into numerical day intervals.
5. Removed redundant data.
6. Loaded the cleaned dataset into PostgreSQL.
7. Used SQL for data analysis.
8. Created visualizations and dashboards to identify customer behavior patterns.

## 📊 Key Analysis Areas

- Customer age groups
- Purchase frequency
- Purchase amount
- Customer segments
- Shopping behavior
- Customer purchasing patterns

## 📁 Project Files

| File | Description |
|---|---|
| `customer_behavior_analysis.py` | Data cleaning and PostgreSQL loading |
| `customer_behaviour.sql` | SQL analysis queries |
| `customer_shopping_behavior.csv` | Dataset |
| `.gitignore` | Prevents sensitive environment files from being uploaded |

## 🔐 Security

Database credentials are stored in a `.env` file and are excluded from version control using `.gitignore`.

## 🚀 How to Run

Install the required Python packages:

```bash
pip install pandas numpy sqlalchemy psycopg2-binary python-dotenv