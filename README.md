# Airline-Performance-Analysis
Data Visualization and Predictive Analysis for Airline Performance using Python, Tableau, and Power BI.

👨‍💻 Author
Rishabh Rathi
Roll No: 16014124051
Branch: Computer and Communication Engineering (CCE)
K. J. Somaiya College of Engineering

📘 Project Overview
This project analyzes airline performance data to identify trends in flight delays, punctuality, and route efficiency.
The dataset was cleaned using Python (pandas), visualized using Tableau, and made interactive using Power BI.


🧹 Python Data Cleaning

The airline_data_cleaning.py script performs the following steps:

Removes unnecessary columns and keeps relevant fields such as flight times, delays, origin, and destination.
Converts delay and distance columns to numeric data types using pd.to_numeric().
Handles missing and invalid values safely.
Creates new columns: Date, Cancelled, On-time, and Route.
Maps three-letter airport codes to full airport and city names.
Saves the final cleaned file as clean_airlines_named_route.csv.


📊 Visualization Tools

Tableau:
Average Arrival Delay by Airline
Flights Departed Early or Delayed
On-Time vs Delayed Flights
Delay by Route
Monthly Delay Pattern

Power BI:
KPI Cards (Total Flights, Average Delay, On-time %, Cancellations)
Delay by Airline
Monthly Delay Trend
On-Time vs Delayed Distribution
Top Routes Dashboard

📁 Files Included
File	Description
flights.csv	Original raw dataset
clean_airlines_named.csv	Cleaned dataset used for visualization
airline_data_cleaning.py	Python script for cleaning
Rishabh_51_DV_miniproject.pdf	Final IEEE-style project report
Tableau_Dashboard_Screenshots/	Screenshots of Tableau visuals
PowerBI_Dashboard_Screenshots/	Screenshots of Power BI visuals

🧠 Tools Used
Python (pandas, datetime)
Tableau Desktop
Microsoft Power BI

🎯 Outcome
The project successfully highlights airline punctuality trends, busiest routes, and delay patterns across carriers.
It demonstrates how data visualization helps identify inefficiencies and supports better operational decisions in aviation.
