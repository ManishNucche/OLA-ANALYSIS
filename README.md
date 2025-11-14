# Ola Ride Analysis – Power BI Project

## 📘 Project Overview
This project analyzes Ola ride data across multiple cities to understand rider behavior, cancellation patterns, revenue metrics, and operational performance.  
The goal is to help ride-hailing businesses improve **driver allocation, cancellation reduction, pricing strategy, and customer satisfaction**.

---

## 🎯 Objectives
- Analyze average rider arrival time  
- Identify most common ride cancellation reasons  
- Compare city-wise ride performance  
- Analyze ride types (Mini, Prime, Auto, Bike)  
- Track demand patterns by time of day  
- Calculate KPIs using DAX  

---

## 🛠 Tools & Skills Used
- **Power BI** – Dashboarding  
- **Power Query** – Data cleaning & transformation  
- **DAX** – KPI creation  
- **Excel** – Initial preprocessing (if used)

---

## 📂 Workflow

### **1. Data Cleaning – Power Query**
- Removed duplicates & errors  
- Standardized date/time formats  
- Cleaned categorical fields (City, Ride Type, Cancel Reason)  
- Created custom columns for:  
  - Ride Duration  
  - Time Slot (Morning/Afternoon/Evening/Night)  

### **2. Data Modeling**
- Fact Table: Rides  
- Dimensions: Cities, Ride-Type, Cancellation Reason, Time Slots  

### **3. DAX Measures Created**
- Total Rides  
- Total Revenue  
- Avg Ride Distance  
- Avg Arrival Time  
- Cancellation Rate  
- Ride-Type Share %  
- Peak-Hour Demand  

### **4. Dashboard Pages**
- **Overview Dashboard**  
- **City-Level Performance**  
- **Ride Type & Vehicle Category Analysis**  
- **Cancellation Insights**  
- **Time-Based Demand Trends**

---

## 🔥 Key Insights
- **Peak demand** occurs between **7–10 AM** and **6–9 PM** across all major cities.  
- **Bike rides** have the highest ride count but lowest revenue per ride.  
- **Prime Sedan** and **Prime SUV** generate the highest revenue.  
- Top cancellation reasons:  
  - *Driver cancelled*  
  - *No cabs available*  
  - *High surge pricing*  
- City X shows **highest cancellation rate** → needs driver supply balancing.  
- Avg arrival time varies drastically between cities (e.g., 5 min vs 11 min).  

---

## 📸 Dashboard Preview

<img width="1471" height="829" alt="Screenshot 2025-07-10 001424" src="https://github.com/user-attachments/assets/9ea6fdd9-8565-453a-aaa5-6113a3d83f6d" />

---

<img width="1472" height="832" alt="Screenshot 2025-07-10 001458" src="https://github.com/user-attachments/assets/9fd4c7d4-ffcb-4400-b211-e647c9c99b9c" />

---

<img width="1473" height="827" alt="Screenshot 2025-07-10 001519" src="https://github.com/user-attachments/assets/017cb2af-0ac3-42cd-ae33-7ab73aea870c" />

---

<img width="1472" height="833" alt="Screenshot 2025-07-10 001544" src="https://github.com/user-attachments/assets/4ab39348-bece-4ce2-93c8-61bc530d784e" />

---

<img width="1478" height="828" alt="Screenshot 2025-07-10 001609" src="https://github.com/user-attachments/assets/64ec0e43-8b91-46ee-ad38-e5dd9dba03b9" />

---

👨‍💻 Author
Manish Nucche
Aspiring Data Analyst
GitHub: https://github.com/ManishNucche
LinkedIn: https://www.linkedin.com/in/manishnucche/
