# Enhancing FMCG Supply Chain Performance

## Project Overview

This project aims to enhance the supply chain performance in the FMCG (Fast-Moving Consumer Goods) sector by analyzing key delivery metrics, identifying areas of improvement, and providing actionable insights. The primary focus is on improving delivery performance, boosting customer satisfaction, and optimizing overall operations.

---

## **Table of Contents**

- [Project Objective](#project-objective)
- [Data Description](#data-description)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Analysis Process](#analysis-process)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Tech Stack](#tech-stack)
- [Project Setup](#project-setup)
- [License](#license)

---

## **Project Objective**

The objectives of this project are as follows:

### (A) **Improving Delivery Performance**:
   - Addressing causes of delays and incomplete deliveries to ensure timely and accurate order fulfillment.

### (B) **Boosting Customer Satisfaction**:
   - Meeting on-time and in-full delivery targets to build reliability and customer trust.

### (C) **Optimizing Operations**:
   - Providing insights to streamline logistics and inventory management based on key KPIs like OTIF percentage, on-time percentage, and in-full percentage.

---

## **Data Description**

The dataset used in this project contains several tables providing crucial information related to customers, products, orders, and delivery performance:

- **dim_customers**: Customer-related information such as customer ID, name, and city.
- **dim_products**: Product details, including product name, category, and ID.
- **dim_date**: Date-related data to track delivery schedules.
- **dim_targets_orders**: Delivery performance targets for each customer (e.g., OTIF, on-time, and in-full targets).
- **fact_order_lines**: Order-specific details, including quantities and delivery dates.
- **fact_orders_aggregate**: Aggregated order data, showing on-time, in-full, and OTIF statuses.

---

## **Key Performance Indicators (KPIs)**

1. **OTIF Percentage**: Measures orders delivered on time and in full, reflecting overall delivery reliability.
2. **On-Time Percentage**: Tracks the percentage of orders delivered on schedule.
3. **In-Full Percentage**: Measures the percentage of orders delivered in complete quantities.
4. **Total Orders**: Provides the total number of orders placed, offering context for other metrics.

---

## **Analysis Process**

### 1. **Data Import**:
   - Imported relevant data from different sources into Power BI for analysis.

### 2. **Data Cleaning**:
   - Cleaned and transformed the data to ensure accuracy and completeness for analysis.

### 3. **Data Modeling**:
   - Established relationships between different data tables and created calculated columns for KPIs.

### 4. **KPIs Creation**:
   - Defined KPIs such as OTIF percentage, on-time percentage, in-full percentage, and total orders to measure delivery performance.

### 5. **Dashboard Creation**:
   - Developed an interactive dashboard to visualize KPIs and trends, providing a comprehensive view of the data.

### 6. **Insights**:
   - Analyzed the data to derive actionable insights for improving supply chain operations.

### 7. **Recommendations**:
   - Provided recommendations to optimize delivery performance and enhance overall supply chain efficiency.

---

## **Insights**

1. **High Late Delivery Rates by City**:
   - Ahmedabad leads in late deliveries with 37.26%, followed by Vadodara at 36.94%. Surat has the lowest late delivery rate at 25.8%.

2. **Top Customers with Late Deliveries**:
   - Lotus Mart and Acclaimed Stores top the list with the highest number of late deliveries, followed by Coolblue, Rel Fresh, and Vijay Store.

3. **Incomplete Deliveries by Category**:
   - Categories like Beverages, Dairy, and Food show an equal percentage of incomplete deliveries, each contributing 33.33% to the overall late or incomplete deliveries.

4. **Underperforming OTIF Targets by City**:
   - Vadodara has the highest rate of orders falling below the OTIF target (37.73%), followed by Ahmedabad and Surat.

5. **Top Customers Falling Below OTIF Targets**:
   - Lotus Mart and Acclaimed Stores have the most orders failing to meet OTIF targets, indicating challenges in meeting customer-specific requirements.

6. **Achieved OTIF Targets by Category**:
   - Across all product categories (Beverages, Dairy, Food), OTIF target achievement rates remain consistent at 33.33%, suggesting uniform issues across categories.

---

## **Recommendations**

1. **Focus on High Late-Delivery Areas and Key Customers**:
   - Improve logistics in Ahmedabad and Vadodara, and address the specific delivery challenges faced by customers like Lotus Mart and Acclaimed Stores to reduce delays.

2. **Strengthen Communication with Customers**:
   - Implement real-time updates to keep customers, especially Lotus Mart and Coolblue, informed on delivery status, improving satisfaction even when delays occur.

3. **Boost OTIF Performance**:
   - Set incremental OTIF improvement goals for underperforming cities and customers, focusing on Vadodara and Ahmedabad. Regularly monitor and adjust strategies based on delivery performance trends.

---

## **Tech Stack**

- **Power BI**: Data analysis, dashboard creation, and visualization.
- **DAX (Data Analysis Expressions)**: Used for calculating key performance metrics (KPIs) in Power BI.
- **Excel/CSV**: Data storage, cleaning, and transformation.

---
