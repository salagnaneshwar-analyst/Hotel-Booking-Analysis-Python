# Hotels Data Analysis Project

## Project Overview
This project analyzes hotel booking and performance data for AtliQ Hotels, a hospitality company operating across multiple cities. The purpose of the analysis is to understand revenue trends, booking behavior, occupancy levels, and capacity utilization using Python. The project converts raw hotel data into meaningful business insights that support better decision-making.

---

## Business Objectives
- Analyze hotel performance across cities and properties
- Understand revenue contribution by hotel and room category
- Measure occupancy percentage and capacity utilization
- Identify overbooking situations
- Support data-driven operational and pricing decisions

---

## Datasets Used
The analysis is based on five datasets:

**dim_date.csv**  
Contains date-related information such as week number and day type (weekday or weekend).

**dim_hotels.csv**  
Contains hotel details including property ID, hotel name, and city.

**dim_rooms.csv**  
Contains room categories and room class information.

**fact_bookings.csv**  
Contains detailed booking-level data including booking dates, room category, booking status, and revenue.

**fact_aggregated_bookings.csv**  
Contains aggregated booking data such as total capacity and successful bookings per property and date.

---

## Tools and Technologies
- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## Project Workflow
1. Loaded all datasets using Pandas
2. Explored data structure, columns, and data types
3. Cleaned and formatted data, including date conversions
4. Merged fact and dimension tables for analysis
5. Performed exploratory data analysis
6. Calculated key business metrics
7. Generated insights and recommendations

---

## Key Metrics Calculated
- Total Revenue
- Total Bookings
- Successful Bookings
- Occupancy Percentage
- Capacity Utilization
- Revenue by City
- Revenue by Hotel
- Revenue by Room Category

**Occupancy Percentage Formula**  
Occupancy Percentage = (Successful Bookings / Capacity) × 100

---

## Key Insights
- A small number of cities and hotels contribute a large share of total revenue
- Premium room categories generate higher revenue but have lower booking volume
- Economy room categories show higher occupancy but lower revenue per booking
- Occupancy rates are higher on weekends compared to weekdays
- Some hotels experience bookings greater than available capacity, indicating overbooking
- Pricing and capacity planning improvements can enhance operational efficiency

---

## Business Recommendations
- Improve capacity planning for high-demand properties
- Apply dynamic pricing during weekends and peak demand periods
- Focus on high-occupancy but low-revenue room categories
- Monitor and control overbooking to improve customer experience

---

