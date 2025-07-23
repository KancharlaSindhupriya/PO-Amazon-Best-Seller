# 📦 Amazon Best Seller Software Analysis (PO Project)

This project focuses on analyzing the **Amazon Best Seller Software Dataset** using **Python** and **MySQL**. The goal is to perform **data cleaning**, **database integration**, and **analytical computation** to extract valuable business insights.


## 📊 Project Overview

🔍 **Dataset**: [Amazon Best Seller Software Dataset](https://www.kaggle.com/datasets) (CSV format)
🧰 **Technologies Used**: Python, Pandas, NumPy, MySQL, MySQL Connector
📂 **Main Files**:
  - `Amazon.ipynb` – Main Jupyter notebook for data analysis
  - `AmazonBestSellerRevature.csv` – Raw dataset used in the project

## 📌 Key Steps & Process

### 1. 🗃️ Dataset Acquisition
- Downloaded the dataset from **Kaggle**
- Saved locally in CSV format for use in Python

### 2. 🐍 Python File Handling
- Used Python’s file handling methods to safely read the CSV file
- Handled exceptions and edge cases for reliable loading

### 3. 🧹 Data Cleaning & Transformation
- Loaded into **Pandas DataFrame**
- Cleaned data by:
  - Removing null/missing values
  - Stripping unwanted symbols (e.g., `$`, `%`)
  - Converting types (e.g., prices to `float`, dates to `datetime`)
  - Removing duplicates
  - Standardizing column names

### 4. 🛢️ MySQL Integration
- Designed a normalized **MySQL schema** for the dataset
- Connected Python to MySQL using `mysql.connector`
- Inserted cleaned data into MySQL tables

### 5. 📈 Data Analysis
Used **Pandas, NumPy**, and **SQL Queries** to extract insights like:

- Top 10 best-selling software products by rating
- Pricing trends across software categories
- Most-reviewed categories and their average ratings
- Comparison of Free vs Paid software performance
- Outliers in pricing and ratings

### 6. 🖥️ Console Output
Displayed insightful summaries in the console, such as:

- 📌 Top 10 Rated Software
- 💰 Average Price per Category
- ⭐ Rating vs Review Correlation
- ⚠️ Outliers in Price & Ratings


## 🧠 Skills Practiced

- Data Cleaning & Preprocessing  
- Relational Database Design  
- Python-MySQL Connectivity  
- Data Aggregation and Grouping  
- Statistical & Visual Insights


## 🧪 How to Run

1. Clone the repository:
  
   git clone https://github.com/KancharlaSindhupriya/PO-Amazon-Best-Seller.git
   
   cd PO-Amazon-Best-Seller


3. Install dependencies:

   pip install pandas numpy mysql-connector-python
   

4. Run the notebook:
   Open `Amazon.ipynb` in Jupyter Notebook or VS Code and execute the cells.

5. (Optional) Configure MySQL:

   * Create a new database and table schema
   * Update connection credentials in the notebook
   * Run insert queries to push data


## 📂 Repository Contents

| File Name                      | Description                          |
| ------------------------------ | ------------------------------------ |
| `Amazon.ipynb`                 | Main analysis notebook               |
| `AmazonBestSellerRevature.csv` | Original dataset used in the project |


## 👩‍💻 Author

**Sindhupriya Kancharla**
📧 Email: [sindhupriyakancharla04@gmail.com](mailto:sindhupriyakancharla04@gmail.com)
🔗 [GitHub](https://github.com/KancharlaSindhupriya)
🔗 [LinkedIn](https://www.linkedin.com/in/sindhupriyakancharla)


