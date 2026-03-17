# 🚖 Uber Trip Analysis Dashboard (Power BI)

## 📌 Project Overview

This project presents an **interactive Power BI dashboard** built to analyze Uber trip data. It provides insights into **booking trends, revenue generation, trip efficiency, and customer behavior**, helping stakeholders make data-driven decisions.

---

## 🎯 Objectives

* Analyze total bookings and revenue trends
* Understand trip distance and duration patterns
* Identify peak demand hours and days
* Perform location-based analysis for pickups and drop-offs
* Evaluate vehicle type performance

---

## 📊 Dashboards Included

### 1️⃣ Overview Analysis

Provides a high-level summary of key performance indicators:

* **Total Bookings**
* **Total Booking Value**
* **Average Booking Value**
* **Total Trip Distance**
* **Average Trip Distance**
* **Average Trip Time**

#### Key Visuals:

* Booking distribution by **Payment Type**
* Booking distribution by **Trip Type (Day/Night)**
* **Total Bookings by Day** (trend analysis)
* **Vehicle Type Analysis** (KPI comparison)
* **Location Analysis**:

  * Most frequent pickup point
  * Most frequent drop-off point
  * Top 5 locations by bookings
  * Most preferred vehicle per location
  * Farthest trip details

---

### 2️⃣ Time Analysis

Focuses on understanding demand patterns over time.

#### Key Visuals:

* **Bookings by Pickup Time (10-minute intervals)**
* **Bookings by Day of Week**
* **Heatmap (Hour vs Day)** for peak demand identification

---

### 3️⃣ Details Dashboard

Provides granular-level insights for in-depth analysis of Uber trips.

#### Features:

* Detailed trip-level data (pickup, drop-off, fare, distance, time)
* Drill-through functionality from other dashboards
* "View Full Data" bookmark to reset filters
* Enables users to explore raw data interactively

#### Use Case:

* Analyze specific trips based on selected filters
* Investigate anomalies or outliers
* Support deeper business insights

✔ Implemented drill-through functionality to navigate from summary dashboards to detailed trip-level data.

---

## ⚙️ Key Features & Techniques

### 🔄 Dynamic Measure Selection

Implemented using a **Disconnected Table + SWITCH DAX**, allowing users to toggle between:

* Total Bookings
* Total Booking Value
* Total Trip Distance

---

### 🔗 Relationship Handling

Used `USERELATIONSHIP()` to activate an **inactive relationship** for drop-off location analysis.

---

### 🎛️ Interactivity

* Slicers for **Date & City**
* Dynamic titles based on selected measure
* Drill-through for detailed insights
* Bookmark for enhanced user experience
* Clear filter/reset functionality

---

## 📈 Key Insights

* Peak booking hours occur during **9 AM – 6 PM**
* **Weekends** show higher demand compared to weekdays
* Most trips are **short-distance (~3 miles average)**
* Certain locations consistently generate higher bookings
* **UberX** is the most preferred vehicle type

---

## 🛠️ Tools & Technologies

* **Power BI** (Data Visualization & Dashboarding)
* **DAX (Data Analysis Expressions)**
* Data Modeling (Relationships, Measures)

---

## 📷 Dashboard Preview

### Overview Analysis

![Overview Dashboard](./assets/overview.png)

### Time Analysis

![Time Dashboard](./assets/time.png)

### Details Dashboard

![Details Dashboard](./assets/details.png)

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Interact using slicers and filters
4. Use drill-through for detailed insights

---

## 📌 Future Improvements

* Add forecasting models for demand prediction
* Integrate real-time data
* Enhance UI with advanced themes
* Add map-based visualizations

---

## 🙌 Conclusion

This dashboard helps in understanding Uber trip patterns and supports:

* Better pricing strategies
* Efficient driver allocation
* Improved customer experience

---

## 👤 Author

**Dhruv Rapariya**

* GitHub: https://github.com/your-username
* LinkedIn: https://linkedin.com/in/your-profile

---

⭐ If you found this project useful, don’t forget to **star the repository!**
