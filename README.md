# 🛒 Data Engineering Project on Brazilian E-Commerce Dataset (Olist)

This project focuses on performing end-to-end **Data Engineering** using the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_customers_dataset.csv), hosted on Kaggle. The work is implemented using **PySpark on Google Colab**.

## 🔧 Tools & Technologies

* **PySpark**
* **Google Colab**
* **Pandas & Matplotlib (for initial exploration)**
* **Kaggle API (for data access)**

## 📁 Dataset Overview

The dataset contains detailed records from a Brazilian e-commerce platform, including:

* Customers
* Orders
* Order items
* Products
* Payments
* Reviews
* Sellers
* Geolocation

## ✅ Project Steps

### 1. 📥 Data Ingestion & Exploration

* Loaded data directly from Kaggle using the API
* Explored schema, data types, and distribution of key variables using PySpark DataFrames

### 2. 🧹 Data Cleaning & Transformation

* Handled missing and inconsistent values
* Applied data type casting
* Created clean and standardized formats for joins and aggregations

### 3. 🔗 Data Integration & Aggregation

* Joined datasets (e.g., orders, customers, products, sellers)
* Aggregated order values, delivery performance, and review scores
* Generated customer-level and seller-level metrics

### 4. 🚀 Performance Optimization

* Used partitioning and caching to speed up processing
* Applied optimized joins and column pruning
* Minimized shuffle by appropriate key-based aggregations

### 5. 📊 Data Serving

* Final curated DataFrames exported to CSV/Parquet
* Ready for use in reporting, dashboarding, or further ML modeling

## 📈 Outcome

The final output is a set of clean, joined, and aggregated datasets, useful for business insights like:

* Top-performing sellers
* Average delivery delays
* Payment method trends
* Review trends by category

## 🚀 How to Run

1. Open the notebook on Google Colab
2. Mount Google Drive and install required packages
3. Use Kaggle API to download the dataset
4. Run the PySpark code cells step-by-step

## 📌 Future Enhancements

* Integrate with BigQuery or Delta Lake for storage
* Schedule pipelines using Apache Airflow
* Serve data to a dashboard (e.g., Power BI or Google Data Studio)

