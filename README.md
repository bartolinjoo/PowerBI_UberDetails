# 🚗 Uber Trip Analysis – Power BI Projectt

Interactive Power BI dashboard for Uber trip analysis, featuring dynamic KPIs, time heatmaps, and location insights to support data-driven decisions on bookings, revenue, and trip efficiency.

---

## 📁 Project Structure

- **Data Model:** Relational model with tables related to trip details, vehicle types, locations, and a calendar table for date-based analysis.
- **DAX Measures:** Total Bookings, Total Booking Value, Average Booking Value, Total Distance, Average Distance, Average Trip Time, Most Frequent Pickup/Dropoff Points, Day vs Night Trip Analysis.
- **Report Pages:**
  - **Overview Analysis** – high-level KPIs and trip summary; breakdown by payment type, trip type (day/night), booking trends, and location insights.
  - **Time Analysis** – time-series breakdown of bookings and trends across the calendar (e.g., by day of week, hour of day).
  - **Details** – detailed trip-level data; supports drillthrough analysis by location, date, or vehicle type.

---

## 📦 Files in the Repository

- `Uber Details.pbix` – Power BI report file  
- `README.md` – project documentation

---

## 🧠 Dynamic Visuals & UX

- **Custom left-side navigation panel** with icons and page bookmarks (**Overview**, **Time**, **Details**)
- **Dynamic KPIs** update based on slicers (**Date** and **City**), showing key metrics:
  - **Total Bookings**
  - **Total Booking Value**
  - **Average Booking Value**
  - **Total Trip Distance**
  - **Average Trip Distance**
  - **Average Trip Time**
- **Tab buttons** ("**Total Bookings**", "**Total Booking Value**", "**Total Trip Distance**") switch the main metric visualizations dynamically
- **Heatmap chart** (Hour vs Day) highlights booking intensity patterns throughout the week
- **Line and area charts**:
  - **Total Bookings by Pickup Time**
  - **Total Bookings by Day Name**
- **Responsive slicers** (**Date** and **City**) filter all visuals in real time
  
- ---

## 🛠️ Tools & Technologies

- Power BI Desktop  
- Power Query  
- DAX (Data Analysis Expressions)

---

