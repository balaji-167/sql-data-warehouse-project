# 📊 SQL Data Warehouse Project

> End-to-End Data Warehouse Solution using SQL Server  
> Implementing ETL Pipelines, Layered Architecture, and Dimensional Modeling (Star Schema)

---

## 🚀 Project Overview

This project demonstrates the design and implementation of a scalable Data Warehouse using Microsoft SQL Server.

It follows a structured **Bronze → Silver → Gold** layered architecture to transform raw operational data into business-ready analytical models.

The goal of this project is to:

- Consolidate CRM & ERP data
- Clean and standardize raw datasets
- Build a dimensional data model
- Enable analytical reporting using SQL
- Follow industry best practices in Data Engineering

---

## 🏗️ Architecture Overview

The project follows a Medallion Architecture pattern:

### 🥉 Bronze Layer – Raw Data

- Stores raw source data as-is
- Preserves original values for traceability
- Acts as the ingestion layer

### ⚙️ Silver Layer – Cleaned & Transformed Data

- Cleans and standardizes data
- Removes duplicates
- Applies transformations
- Prepares structured tables

### 🏆 Gold Layer – Analytics Layer

- Implements Star Schema
- Creates Fact and Dimension tables
- Optimized for reporting & BI queries

---

## 🗂️ Repository Structure

```
sql-data-warehouse-project/
│
├── datasets/        # Raw source files
├── scripts/         # SQL scripts (ETL & modeling)
│   ├── bronze/
│   ├── silver/
│   └── gold/
├── tests/           # Data validation scripts
├── docs/            # Documentation & diagrams
├── README.md
└── LICENSE
```


---

## 🛠️ Tech Stack

- Microsoft SQL Server
- T-SQL
- SQL Server Management Studio (SSMS)
- Git & GitHub

---

## 🔄 ETL Workflow

1. Load raw data into Bronze tables  
2. Clean & standardize data in Silver layer  
3. Build Fact & Dimension tables in Gold layer  
4. Run analytical queries for business insights  

---

## 📊 Dimensional Model (Star Schema)

The Gold layer includes:

- `fact_sales`
- `dim_customer`
- `dim_product`

---

## 📸 Project Screenshots

### 🧱 Architecture Diagram


![Architecture Diagram](https://github.com/user-attachments/assets/5722084b-88ee-4284-b6d8-7e8fedd11078)

---

### ⭐ Star Schema Diagram

![Star Schema](https://github.com/user-attachments/assets/51e150fa-d093-46e2-9e65-9bf8fd83625a)

---

### 📊 Sample Query Output

(docs/sample-query.png)
![Query Result](https://github.com/user-attachments/assets/b4010975-37f6-4172-ab35-1e76adcf054f)

---

## 📈 Sample Business Use Cases

- Top 10 Customers by Revenue
- Monthly Sales Trends
- Product Performance Analysis
- Revenue by Region

---

## 🧪 Data Quality & Testing

Validation scripts ensure:

- No duplicate records
- No null foreign keys
- Referential integrity maintained
- Data consistency across layers

---

## ▶️ How To Run

1. Install SQL Server & SSMS
2. Create a new database
3. Run Bronze layer scripts
4. Run Silver transformation scripts
5. Run Gold modeling scripts
6. Execute analytics queries

---

## 💡 Key Highlights

✔ Industry-standard layered architecture  
✔ Clean and modular SQL scripts  
✔ Dimensional modeling (Star Schema)  
✔ Business-focused analytical queries  
✔ Production-style ETL workflow  

---

## 📌 Future Improvements

- Automate ETL using SQL Agent
- Connect to Power BI for dashboarding
- Add incremental loading logic
- Add performance indexing

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

Balaji Reddy  
GitHub: https://github.com/balaji-167
