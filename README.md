# Power BI Sales Dashboard (Customers & Orders)
## 📌 Project Overview
This project is a beginner-level Power BI dashboard built using two tables: Customers and Orders. The goal of this dashboard is to analyze sales performance, customer count, and product-wise sales trends using interactive visuals and slicers.

This project helped me understand the end-to-end Power BI workflow, from data import to dashboard creation.

---

## 🗂️ Data Sources
The project uses two Excel files:
- **Customers table** – customer details
- **Orders table** – order, product, sales, and order date information
> *Datasets were taken from a YouTube tutorial description and used for learning purposes.*

---

## 🔗 Data Modeling & Transformation
- Imported both Excel files into **Power BI Desktop**
- Created a **relationship** between Customers and Orders tables
- Handled missing NULL values in the Customers table using **DAX `COALESCE()`**
- Combined **First Name** and **Last Name** columns using **Power Query**

---

## 🛠️ Tools & Technologies Used
- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

## 📈 Dashboard Features

The dashboard contains the following visuals:

1. **Bar Chart** – Sum of sales by product
2. **Donut Chart** – Sum of sales by product category
3. **Line Chart** – Sales trend by year and quarter using order_date
4. **Card Visuals**:
   - Total number of orders
   - Total number of customers
   - Total sales
5. **Slicers**:
   - Country
   - Product_category
   - Order_date range

---

## 🔍 Key Insights
- Identified top-selling products based on total sales
- Analyzed sales distribution across product categories
- Observed sales trends across different years and quarters
- Enabled interactive filtering by country, product category, and order_date

---

## 📷 Dashboard Preview
![Sales Dashboard](Screenshots/Sales_dashboard-1.png)

---

## 📚 What I Learned
- Importing and modeling data in Power BI  
- Creating relationships between tables  
- Using **DAX** to handle null values  
- Performing data transformations with **Power Query**  
- Building interactive dashboards using slicers and visuals  

---

## 🚀 Future Enhancements
- Add more datasets for deeper analysis  
- Implement advanced DAX measures  
- Improve dashboard layout and design  
- Add KPIs like Average Order Value (AOV)  

---

### 📁 Repository Structure

```text
PowerBI-Sales-Dashboard-Customers-Orders/
│
├── Datasets/                           # Datasets used for the project
│
├── Screenshots/                        # PNG files of the dashboard
│   ├── Sales_dashboard-1.png           # PNG file - 1
│   ├── Sales_dashboard-2.png           # PNG file - 2
│
├── Sales_Dashboard.pbix                # PBIX file of the sales dashboard
│
├── README.md                           # Project overview
├── LICENSE                             # License information
```

### 👩‍💻 About Me : 
Hi there! I'm Rahul Gundoju  
 - 🔍 Passionate about **Data Analysis, Business Insights, and Visualization**  
 - 🎯 Actively seeking **Data Analyst opportunities**  
 - 🛠  Skilled in **SQL, Python (Pandas/Numpy), Excel, Power BI**  
 - 🎓 Artificial Intelligence & Data Science Graduate
 - 🔗 LinkedIn: www.linkedin.com/in/rahul-gundoju
 - 📧 Email: rahulgundoju777@gmail.com
 - 📍 Hyderabad, India  
