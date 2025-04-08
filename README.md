# Microsoft-Fabric-End-to-End-Project
Microsoft Fabric End-to-End Project. It covers Lakehouse, SQL Endpoint, semantic model and creating Power BI dashboard

## 📘 Project Overview

This project demonstrates a full **end-to-end data pipeline** using **Microsoft Fabric**, from raw data ingestion to a live Power BI dashboard. The use case revolves around **Fixed Deposits (FDs)** made by three individuals in various banks.

---

## 🛠️ Tools & Technologies Used
- Microsoft Fabric (Lakehouse)
- SQL Endpoint
- Semantic Model
- Power BI

---

## 🔄 Workflow

1. **Lakehouse Ingestion**  
   - Loaded raw FD data into the Lakehouse without any transformation.

2. **SQL-Based Transformation**  
   - Used the **SQL Endpoint** to:
     - Cast data types (e.g. to converting the data types of dates)
     - Create **custom columns** like:
       - `InterestRate`
       - `NumberOfYears`
       - `isExpired` flag
       - `CurrentValue` of the FD

3. **Semantic Model Creation**  
   - Built a **Default Semantic Model** for structured reporting and analytics.

4. **Power BI Dashboard**  
   - Developed a report highlighting:
     - 📅 Total principal and total amount, average rate of interest,
     - 🏦 Bank-wise FD allocation
     - 💸 Interest Rate distribution
     - ✅ Expired vs Active deposits

---

## 📊 Key Insights Delivered
- Interest earning patterns across banks
- Value growth based on tenure and rate
- Personal portfolio performance for each investor

---

## 🚀 Learning Outcomes
- Hands-on experience with **Microsoft Fabric Lakehouse architecture**
- SQL transformations within **Fabric's SQL Endpoint**
- Creating and managing **Semantic Models**
- Building dynamic dashboards with **Power BI**

---

## 🙌 Author

**Anoj Nisal**  
📧 anojn123@gmail.com  
🌐 [www.linkedin.com/in/anoj-nisal]
