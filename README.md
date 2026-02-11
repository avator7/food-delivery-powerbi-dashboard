# Food Delivery Business & Operations Dashboard (Power BI)

This project demonstrates a multi-page Power BI dashboard built on food-delivery transactional data to analyze business performance, delivery operations and customer churn.

The dashboard is designed to simulate a real-world food delivery platform use case and is suitable for business, operations and analytics teams.

---

## Project Overview

The goal of this project is to provide a single reporting layer for:

- Business performance (orders, revenue, categories, cities)
- Delivery operations (delivered, delayed and cancelled orders)
- Customer behavior and churn
- Restaurant and menu performance

---

## Dashboard Pages

### 1. Business Overview
- Total Orders
- Total Revenue
- Average Order Value
- Active Customers
- Orders and revenue by city
- Orders by category
- Order trend by date

---

### 2. Delivery & Operations
- Delivered, delayed and cancelled orders
- Delivery status by city
- Delivery status by restaurant
- Delivery trend over time

---

### 3. Customer & Churn Analysis
- Active vs inactive customers
- Churn percentage
- Churn by city
- Churn by age group
- Loyalty points vs churn
- Ratings vs churn

---

### 4. Restaurant & Menu Performance
- Top restaurants by number of orders
- Top restaurants by revenue
- Top dishes by quantity
- Category-wise revenue
- Restaurant ratings and order volume

---

## Key Measures Created (DAX)

- Total Revenue
- Average Order Value
- Delivered Orders
- Delayed Orders
- Cancelled Orders
- Active Customers
- Inactive Customers
- Churn Percentage
- Average Rating

---

## Data Model

This project uses a single fact-style table for simplicity and demonstration purposes.

Calculated measures and a derived Age Group column were created for segmentation and churn analysis.

---

## Tools & Skills Used

- Power BI Desktop
- DAX (measures and calculated columns)
- Data preparation and data typing
- Business and operations analytics
- Dashboard design and storytelling

---

## Automation-Ready Design

The dashboard is designed to support automated refresh from upstream Python or ETL pipelines.
The data source can be replaced with an automatically generated CSV or database table without changing the report logic.

---

## Repository Structure

food-delivery-powerbi-dashboard
│
├── data
│ └── sample_foodpanda_dataset.csv
│
├── powerbi
│ └── Food_Delivery_Dashboard.pbix
│
├── screenshots
│ ├── overview.png
│ ├── delivery.png
│ ├── churn.png
│ └── restaurant.png
│
└── README.md
