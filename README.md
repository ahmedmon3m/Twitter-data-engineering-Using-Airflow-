# 🚀 Twitter Data Engineering Pipeline with Apache Airflow  

### **Extract, Transform, and Load (ETL) Twitter Data using Apache Airflow, PostgreSQL, and Tweepy.**  

---

## 📌 **Project Overview**  
This project is a **Data Engineering pipeline** that extracts real-time Twitter data using **Tweepy**, processes it using **Apache Airflow**, and stores it in **PostgreSQL** for analytics. The pipeline follows the **ETL process**:  

1️⃣ **Extract** - Fetch real-time tweets using Twitter API.  
2️⃣ **Transform** - Clean, filter, and structure the data.  
3️⃣ **Load** - Store structured data in a PostgreSQL database for further analysis.  

---

## 🛠️ **Tech Stack Used**  
✅ **Apache Airflow** - Orchestration & workflow automation  
✅ **Tweepy (Twitter API)** - Data extraction  
✅ **PostgreSQL** - Data storage & querying  
✅ **Docker & Docker-Compose** - Containerized deployment  
✅ **Python (pandas, Tweepy, SQLAlchemy)** - Data processing  
✅ **Jupyter Notebook** - Exploratory data analysis (EDA)  

---

## 🎯 **Project Workflow**  

### **1️⃣ Data Extraction**  
- Connect to **Twitter API** via **Tweepy**  
- Stream tweets based on **hashtags & keywords**  
- Save raw data in **JSON format**  

### **2️⃣ Data Transformation**  
- Convert JSON to structured format  
- Extract meaningful insights (**timestamp, user, text, location**)  
- Remove **spam, retweets, and unwanted data**  

### **3️⃣ Data Loading**  
- Store cleaned tweets in **PostgreSQL database**  
- Use **SQL queries** to analyze tweet trends  

### **4️⃣ Airflow Orchestration**  
- Automate data extraction, cleaning & storage using **Apache Airflow DAGs**  
- Monitor & log **workflow status**  

---
