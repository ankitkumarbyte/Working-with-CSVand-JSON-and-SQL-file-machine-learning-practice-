# Python Data Handling: CSV, JSON, and SQL

This repository contains Jupyter Notebooks that demonstrate how to work with **CSV files**, **JSON-style structured data**, and **SQL databases** using Python.  
The project is beginner-friendly and focuses on practical, real-world data handling using popular Python libraries.

---

## 📌 Project Overview

This project covers:
- Reading and processing CSV files
- Fetching CSV data from online sources
- Working with structured/tabular data using Pandas
- Connecting Python with a MySQL database
- Executing SQL queries through Python
- Converting SQL query results into Pandas DataFrames

---

## 📂 Project Structure

.
├── Working_with_CSV_and_JSON_File.ipynb
├── Working with SQL File.ipynb
└── README.md


---

## 📘 Notebook Descriptions

### 📄 Working_with_CSV_and_JSON_File.ipynb

This notebook demonstrates how to work with CSV and structured data using Python.

#### Topics Covered:
- Importing required Python libraries
- Reading CSV files from local storage
- Downloading CSV data from a URL
- Using `requests` to fetch external data
- Converting raw CSV text into Pandas DataFrames
- Inspecting data using:
  - `.head()`
  - `.tail()`
  - `.info()`
  - `.describe()`

#### Libraries Used:
- `pandas`
- `requests`
- `io.StringIO`

---

### 🗄️ Working with SQL File.ipynb

This notebook focuses on database connectivity and SQL operations using Python.

#### Topics Covered:
- Connecting Python to a MySQL database
- Using `mysql-connector-python`
- Creating a database connection
- Writing and executing SQL queries
- Fetching query results
- Loading SQL query results into Pandas DataFrames
- Displaying and analyzing database tables

#### Database Details:
- Database type: MySQL
- Sample database used: `world`

#### Libraries Used:
- `mysql.connector`
- `pandas`

---

## 🚀 How to Run the Project

Clone the repository:

git clone <repository-url>


Navigate to the project directory:

cd <project-folder>


Launch Jupyter Notebook:

jupyter notebook


Open any .ipynb file and run the cells sequentially.

## 🔐 Database Configuration (Important)

Before running the SQL notebook, update the database credentials in the code:

host

user

password

database

Example configuration:

connection = mysql.connector.connect(
    host="localhost",
    user="your_username",
    password="your_password",
    database="world"
)



## 📝 Notes

Ensure the MySQL server is running before executing SQL queries.

Internet access is required to fetch CSV data from URLs.

The SQL notebook assumes the world database already exists.

File paths and credentials may need adjustment based on your system.

## 🎯 Learning Objectives

By completing this project, you will learn:

How to handle CSV and structured data in Python

How to fetch external data from URLs

How to connect Python with relational databases

How to execute SQL queries using Python

How to analyze tabular data using Pandas

## 👨‍💻 Intended Audience

This project is suitable for:

Beginners learning Python for data analysis

Students working on college or university assignments

Anyone practicing file handling and database connectivity in Python

## 📜 License

This project is created for educational purposes and is free to use and modify.
## ⚙️ Requirements

Make sure the following are installed on your system.

### Python Libraries
```bash
pip install pandas requests mysql-connector-python


## Software Requirements

Python 3.x

Jupyter Notebook or JupyterLab

MySQL Server

MySQL client access credentials


