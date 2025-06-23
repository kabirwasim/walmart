# 🛍 Walmart Sales Data Analysis

## 📘 Project Overview

This project is an **end-to-end data analysis pipeline** built to derive actionable business insights from Walmart sales data. It combines **Python**, **SQL (MySQL & PostgreSQL)**, and data engineering techniques to clean, transform, and query sales transactions for meaningful conclusions. Ideal for aspiring **Data Analysts** and **Data Engineers** to practice real-world skills in a structured setting.

---

## ✅ What Is This Project?

A complete data analysis workflow that:

* Downloads Walmart sales data from **Kaggle** using the **Kaggle API**.
* Cleans and transforms the dataset with **Python (Pandas & NumPy)**.
* Engineers features like **Total Transaction Amount**.
* Loads the final dataset into **MySQL** and **PostgreSQL** for structured SQL analysis.
* Answers key business questions using advanced SQL queries.

---

## ⚙️ How I Did It

### 1. 🛠 Environment Setup

* Tools: **Visual Studio Code**, Python, SQL (MySQL/PostgreSQL).
* Organized the project into folders for data, scripts, notebooks, and outputs.

### 2. 🔑 Kaggle API Integration

* Retrieved dataset using the Kaggle API.
* Stored the data in a structured `data/` folder.

### 3. 📦 Data Loading

* Installed required libraries:

  ```bash
  pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
  ```
* Loaded data into Pandas DataFrames for initial processing.

### 4. 🔍 Data Exploration

* Used `.head()`, `.describe()`, `.info()` to understand structure, types, and values.

### 5. 🧹 Data Cleaning

* Removed duplicates and missing values.
* Formatted currencies and ensured correct data types (e.g., datetime for dates).

### 6. 🧮 Feature Engineering

* Created `Total_Amount = Unit_Price × Quantity`.
* Added this field to support easier aggregations later.

### 7. 💃 Database Integration

* Used **SQLAlchemy** to connect to **MySQL** and **PostgreSQL**.
* Created tables and inserted cleaned data automatically.
* Verified data insertion with SQL queries.

---

## 🌟 What Is the Impact?

* ✅ **Business Insight**: Helped analyze total sales, product trends, and time-based performance metrics.
* 🧠 **Skills Practiced**: Real-world experience in data cleaning, SQL integration, and pipeline creation.
* 📈 **Scalable Solution**: The structured approach allows future automation, dashboarding, and reporting.
* 💼 **Job-Ready Output**: Mimics actual workflows used in data analyst and data engineer roles.

---

## 📁 Folder Structure

```
walmart-sales-analysis/
│
├── data/                    # Raw and cleaned data files
├── notebooks/               # Jupyter notebooks for exploration
├── scripts/                 # Python scripts for loading & processing
├── sql_queries/             # SQL scripts and examples
├── README.md                # Project documentation
```

---

## 🚀 How to Run the Project

1. Clone the repo and install dependencies.
2. Place your Kaggle API key in `.kaggle/kaggle.json`.
3. Run the data download script or use CLI to pull data.
4. Clean, engineer features, and load into databases.
5. Execute SQL queries to generate business insights.

---

## 📞 Contact

If you have suggestions or want to collaborate, feel free to connect!

---

Enhance Dataset: Adding this calculated field will streamline further SQL analysis and aggregation tasks.

##8. Load Data into MySQL and PostgreSQL
Set Up Connections: Connect to MySQL and PostgreSQL using sqlalchemy and load the cleaned data into each database.
Table Creation: Set up tables in both MySQL and PostgreSQL using Python SQLAlchemy to automate table creation and data insertion.
Verification: Run initial SQL queries to confirm that the data has been loaded accurately.
