# 🛒 Instacart Data Analytics — Power BI Dashboard

An interactive **Power BI dashboard** built to analyze **customer behavior, purchasing patterns, product performance, and reorder activity** across more than **3.3M orders**, **206K customers**, and **49K+ products**.

The dashboard provides a business-focused view of the data, helping identify **high-value customers, recurring purchasing behavior, top-performing products, and demand patterns throughout the day**.

### 📊 Dashboard Highlights

* **3.35M Orders**
* **206K Customers**
* **49K+ Products**
* **59% Reordered Items**
* **2.5M+ Produce Orders**
* **~11.4 Days Average Between Orders**

### 🎯 Key Questions Answered

* When are customers most likely to place orders?
* Which departments and aisles generate the highest demand?
* What products are most frequently purchased?
* How strong is repeat purchasing behavior?
* Which customers are the most engaged?
* Where are the biggest opportunities for retention and personalization?

---

## 🧩 Data Model

The Power BI model was built using the **Gold Views** from the Instacart Data Warehouse project.

<!-- Add your Data Model image here -->

![Instacart Power BI Data Model](<Data Model/Data model.png>)

---

### 🗄️ SQL Data Warehouse Project

The data used in this dashboard comes from the **Gold Views** of the SQL Data Warehouse project.

**[View Data Warehouse Repository](https://github.com/ahmedalaa-1/Instacart_warehouse_project)**

---

### 🔗 Power BI Service

**[View Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMzI5OWUyZGYtMGNhYy00ZmMyLTljNzktNDA2MmM0YzZkOTQ0IiwidCI6IjZhYWE0MDU0LTgzNGEtNGJiMi1hYzIwLWRkM2E0NmJiMzg5MiJ9)**

---

## 📊 Dashboard Pages

### 🟢 Page 1 — Overview

A high-level view of overall business performance, including:

* Total Orders
* Total Users
* Total Products
* Reorder Rate
* Orders by Day & Hour
* Top Departments

<!-- Add Page 1 screenshot here -->

![Instacart Dashboard - Overview](<dashboard/Overview.png>)

---

### 🔵 Page 2 — Customer Behavior

Analyzes customer purchasing frequency and repeat behavior, including:

* Average Days Between Orders
* Average Orders per Customer
* New vs. Reordered Items
* Customer Frequency Segments
* High-Frequency Customers

<!-- Add Page 2 screenshot here -->

![Instacart Dashboard - Customer Behavior](<dashboard/Customers behavior.png>)

---

### 🟣 Page 3 — Products & Categories

Explores product and category performance through:

* Department Performance
* Aisle Performance
* Reorder Rates
* Top Products
* Product Demand Patterns

<!-- Add Page 3 screenshot here -->

![Instacart Dashboard - Products & Categories](<dashboard/Products & Category.png>)

---

## 🔍 Key Insights

### 🔄 Strong Repeat Purchasing

Approximately **59% of items were reordered**, indicating strong recurring purchasing behavior and a significant opportunity to improve customer retention.

### ⏰ Demand Concentration

Orders are heavily concentrated during daytime hours, with the busiest period occurring approximately between **9 AM and 4 PM**.

The highest observed point was:

**Monday at 10 AM → ~54.7K orders**

### 🥦 Produce Leads Demand

**Produce** is the largest department with approximately **2.5M orders** and a reorder rate of around **65%**.

### 👥 High-Frequency Customers

Customers in the **91–100 orders segment** average approximately **98 orders per user**, highlighting a highly engaged customer group.

### 🛒 Fresh Products Drive Repeat Demand

Fresh Fruits, Fresh Vegetables, Milk, and Yogurt are among the strongest aisles for both demand and reorder behavior.

---

## 💡 Business Opportunities

The analysis highlights several potential opportunities:

* **Personalized Product Recommendations**
* **Reorder Reminders**
* **Loyalty Programs**
* **Targeted Customer Segmentation**
* **Demand & Inventory Optimization**

---

## 🛠️ Tools & Technologies

| Technology        | Usage                          |
| ----------------- | ------------------------------ |
| **SQL Server**    | Source Data Warehouse          |
| **Power BI**      | Dashboard & Data Visualization |
| **Power Query**   | Data Preparation               |
| **DAX**           | Measures & Calculations        |
| **Data Modeling** | Analytical Model               |

---

## 📂 Project Structure

```text
Instacart-PowerBI/
│
├── docs/
│   ├── data-model.png
│   ├── page-1-overview.png
│   ├── page-2-customer-behavior.png
│   └── page-3-products-categories.png
│
├── screenshots/
│
└── README.md
```

---

## 🎯 Project Objective

The objective of this project is to transform transactional e-commerce data into **clear, actionable business insights** around:

**Customer Behavior → Product Performance → Reorder Patterns → Business Opportunities**

---

## 👤 Author

**Ahmed Alaa**

Data Analyst | SQL | Power BI | Data Analytics

[LinkedIn](https://www.linkedin.com/in/-ahmedalaa-/)
