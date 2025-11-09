# ✈️ Airline Performance Analysis using Power BI

## 📊 Overview
This project focuses on analyzing and visualizing airline operational data using **Microsoft Power BI**.  
The aim is to uncover insights into flight operations, passenger management, and ticketing trends to support data-driven decision-making in the airline industry.

---

## 🧩 Problem Statement
The airline industry operates in a highly dynamic environment with thousands of daily flights, passenger interactions, and ticket bookings.  
Managing and analyzing this large amount of data is essential for:
- Improving on-time performance,
- Enhancing customer satisfaction, and
- Optimizing resource allocation.

This project streamlines and visualizes airline operations using Power BI to uncover actionable insights.

---

## 🎯 Objectives
- Analyze flight, passenger, and ticket data efficiently.  
- Build a unified data model for airline operations.  
- Create an interactive and dynamic Power BI dashboard.  
- Implement advanced analytics using DAX, slicers, and drill-throughs.  
- Enable automated data refresh and row-level security.

---

## 🗂️ Datasets Used
1. **Flight Information**
   - Columns: `FlightID`, `FlightNumber`, `Airline`, `Destination`, `Status`

2. **Passenger Information**
   - Columns: `PassengerID`, `FlightID`, `SeatNumber`

3. **Ticket Information**
   - Columns: `TicketID`, `FlightID`, `BookingStatus`

All datasets were provided in `.csv` format and imported into Power BI for transformation and analysis.

---

## ⚙️ Tasks & Features Implemented

### 1. Data Preparation
- Extracted and loaded datasets into Power BI via Power Query.
- Performed data cleaning: removed duplicates, handled missing values, standardized column formats.

### 2. Transformation
- Created **Conditional Columns** to classify flights as “Best” or “To Be Improved.”
- Used **Column from Examples** to extract flight numbers.
- Replaced inconsistent values in the `Status` column for uniformity.

### 3. Data Modeling
- Merged datasets (`Flight Information` + `Passenger Information`).
- Created relationships between all datasets based on `FlightID`.
- Defined cardinality for relational integrity.

### 4. DAX Calculations
- Calculated total tickets booked.
- Found total passengers for a specific flight (`FL5011`).
- Created filtered tables for “Best” flights only.

### 5. Visualizations
- **Multi-Card Visual:** Displays total flights, passengers, and airlines.
- **Bar Chart:** Shows passengers per airline.
- **Donut Chart:** Depicts ticket booking status distribution.

### 6. Advanced Visuals
- **Decomposition Tree:** Breakdown by Airline → Destination.
- **Key Influencers:** Identify top factors affecting flight performance.
- **Q&A Visual:** Interactive query-based visualization.

### 7. Interactive Features
- **Slicers:** Filter by Airline, Destination, Status.
- **Bookmarks:** Save multiple dashboard views.
- **Drill-Through:** Navigate from Airline summary → Destination-level detail.

### 8. Dashboard & Deployment
- Created workspace “Airline” on Power BI Service.
- Implemented **Row-Level Security (RLS)** for restricted airline data.
- Configured **Scheduled Refresh** (5 PM daily).

---

## 📈 Key Insights
- Identified airlines with consistent on-time performance.
- Highlighted destinations with frequent delays.
- Improved understanding of passenger and ticketing trends.
- Built a foundation for real-time airline performance monitoring.

---

## 💡 Learnings
- Gained hands-on experience with Power Query and DAX.
- Learned to design effective and interactive Power BI dashboards.
- Understood the end-to-end process of data cleaning, modeling, and visualization.
- Practiced deploying Power BI reports to the Power BI Service.

---

## 🧰 Tools & Technologies
- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Power BI Service**

---

## 🚀 How to View the Report
1. Clone this repository:
   ```bash
   git clone https://github.com/GourabDG36/Power-BI-project.git
## Final dashboard
<img width="1446" height="805" alt="final dashboard" src="https://github.com/user-attachments/assets/807f5ce5-5550-43e7-9111-929a1ed62fe1" />
