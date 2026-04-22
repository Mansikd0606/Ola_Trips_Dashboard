# Ola_Trips_Dashboard

📌 Project Overview

This project focuses on analyzing OLA trips data using Power BI to uncover key business insights such as ride trends, revenue patterns, customer behavior, and operational performance.

The goal is to transform raw trip data into an interactive dashboard that helps stakeholders make data-driven decisions.

🎯 Objectives
- Analyze trip patterns and booking trends
- Identify peak demand periods
- Monitor revenue and performance KPIs
- Understand customer and ride behavior
- Provide actionable insights through visualization

🛠️ Tools & Technologies Used
- Power BI – Data visualization & dashboard creation
- Power Query – Data cleaning and transformation
- DAX (Data Analysis Expressions) – KPI calculations and measures

📂 Dataset Description
The dataset contains information about OLA rides, including:
- Booking ID
- Date & Time
- Ride Distance
- Fare Amount
- Ratings

🔄 Data Preparation Steps
- Removed null and duplicate values
- Converted data types (Date, Numeric fields)
- Created calculated columns (e.g., Month, Day, Time Slots)

📊 Key KPIs Created
- 🚗 Total Trips
- 💰 Total Revenue
- 📈 Average Trip Value
- 📍 Total Distance Covered
- ⏱️ Average Ratings

📈 Dashboard Features
- Trips Trend Analysis (Daily/Monthly)
- Peak Hour Analysis
- Top Locations by Trips & Revenue
- Interactive Filters (Slicers)
- Gender Trips Anlaysis

📌 Key Insights
- Peak ride demand observed during specific hours (e.g., office commute times)
- Certain locations contribute significantly to revenue
- Revenue trends show seasonal or monthly variation

🎨 Dashboard Preview

![](https://github.com/user-attachments/assets/52b06c84-da1a-4ccb-9cff-2ceac457954d)

 # DAX Measures
 1. Find out Total Revenue.
   - ```Total_Revenue = SUM(Data[total_trip_cost])```

 2. Find out Total Trips.
   - ```Total_Trips = COUNT(Data[booking id])```

 3. Find out Total Distance.
   - ```Total_distance = SUM(Data[distance_travelled])```

 4. Find out Average Trip Cost.
   - ```Avg_trip_cost = AVERAGE(Data[total_trip_cost])```

 5. Find out Average Rating.
   - ```Avg_rating = AVERAGE(Data[ratings])```

