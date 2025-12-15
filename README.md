# uber-trip-analysis-powerbi
An interactive Power BI dashboard analyzing Uber trip data to uncover booking trends, revenue insights, trip efficiency, time-based demand patterns, and location analysis using DAX and data modeling.
# 🚕 Uber Trip Analysis Dashboard | Power BI

## 📌 Project Overview
This project is an **end-to-end Business Intelligence solution** developed using **Power BI** to analyze Uber trip data and extract actionable insights.  
The dashboard converts raw trip-level data into **interactive visual reports** that help understand booking behavior, revenue trends, time-based demand, and location performance.

The project is designed to simulate **real-world analytics requirements** faced by ride-hailing companies, enabling data-driven operational and strategic decisions.

---

## 🎯 Business Problem Statement
Ride-hailing platforms like Uber generate massive amounts of trip data daily.  
Without proper analysis, it becomes difficult to:
- Track booking and revenue performance
- Identify peak demand periods
- Optimize driver allocation
- Understand customer travel patterns
- Improve pricing and operational efficiency

This dashboard addresses these challenges by providing **clear KPIs, trend analysis, and drill-down capabilities**.

---

## 🎯 Project Objectives
- Analyze total bookings and revenue performance
- Measure trip efficiency using distance and duration
- Identify peak and off-peak demand periods
- Analyze payment modes and vehicle type usage
- Discover high-demand pickup and drop-off locations
- Enable drill-through analysis for detailed data exploration

---

## 📊 Dashboard Architecture & Pages

### 🟩 Dashboard 1: Overview Analysis
This page provides a **high-level summary** of overall trip performance.

**Key Components:**
- KPI Cards:
  - Total Bookings
  - Total Booking Value
  - Average Booking Value
  - Total & Average Trip Distance
  - Average Trip Time
- Dynamic Measure Selector:
  - Total Bookings
  - Total Booking Value
  - Total Trip Distance
- Analysis by:
  - Payment Type (Cash, Card, Wallet, etc.)
  - Trip Type (Day / Night)
  - Vehicle Type (Matrix with conditional formatting)
- Top 5 Pickup and Drop-off Locations
- Longest (Farthest) Trip Identification

**Purpose:**  
To help stakeholders quickly assess performance and compare trends across different dimensions.

---

### 🟪 Dashboard 2: Time Analysis
This page focuses on **temporal patterns** in Uber trip demand.

**Key Components:**
- Trips grouped by **10-minute pickup intervals**
- Booking trends by **day of the week**
- Heatmap showing **Hour vs Day** demand patterns
- Global dynamic measure applied across all visuals

**Purpose:**  
To identify **peak hours, peak days, and demand fluctuations**, supporting pricing optimization and better driver scheduling.

---

### 🟦 Dashboard 3: Details & Drill-Through View
This page enables **deep data exploration**.

**Key Components:**
- Drill-through from summary visuals to trip-level records
- Grid view displaying detailed trip attributes
- Bookmark to toggle between:
  - Filtered (drill-through) data
  - Full dataset view

**Purpose:**  
To allow analysts and stakeholders to validate insights and investigate specific data points in detail.

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **DAX Measures & Calculated Columns**
- Data Cleaning & Preprocessing
- Data Modeling & Relationship Management
- Disconnected Tables for Dynamic Measures
- Bookmarks & Drill-Through
- Interactive Slicers & Tooltips
- Conditional Formatting & Heatmaps

---

## 📚 Dataset Information
The dataset contains Uber trip data with attributes such as:
- Booking details
- Trip distance and duration
- Vehicle type
- Payment mode
- Pickup and drop-off locations
- Date and time attributes

> The dataset is used strictly for **learning and analytical purposes**.

---

## 📈 Key Insights Generated
- Identified peak booking hours and high-demand days
- Discovered top-performing pickup and drop-off locations
- Analyzed revenue and booking value patterns
- Evaluated vehicle type and payment mode preferences
- Highlighted long-distance trips for operational analysis

---

## 🚀 How to Use This Dashboard
1. Download the `.pbix` file from this repository
2. Open it using **Power BI Desktop**
3. Use slicers and measure selectors to interact with visuals
4. Drill through charts to explore detailed trip-level data
5. Reset filters using bookmarks for fresh analysis

---

## 📌 Key Learnings
- Practical experience with real-world BI requirements
- Advanced DAX and dynamic measure implementation
- Effective dashboard design and storytelling with data
- Translating business questions into analytical solutions

---

## 👤 Author
**Prashant Khari**  
Aspiring Data Analyst | Data Science Enthusiast  

📫 Feel free to connect on LinkedIn and share feedback or suggestions.

---

## ⭐ Support
If you find this project helpful:
- ⭐ Star this repository  
- 💬 Share feedback  
- 🔁 Fork and explore further analytics use cases
