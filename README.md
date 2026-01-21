## ✈️ Airline Occupancy & Revenue Analysis
## 📌 Project Overview

This project analyzes airline operational data to understand how seat occupancy and pricing affect overall revenue. Using SQL and Python, the analysis focuses on identifying under-utilized aircraft, evaluating fare structures, and estimating the revenue impact of improving occupancy rates.

The goal of the project is to support data-driven decision-making that can help airlines improve aircraft utilization and increase profitability.

## 🎯 Business Problem

Airlines face increasing operational costs due to fuel prices, labor shortages, and regulatory pressures. One of the most effective ways to improve profitability without increasing costs is by maximizing seat occupancy.

## This project explores:

Which aircraft have low occupancy rates

How pricing varies across fare classes

How improving occupancy can impact annual revenue

## 🗂️ Dataset Description

The analysis is based on a relational airline database containing the following tables:

flights – flight schedules and aircraft information

seats – seat configuration by aircraft

boarding_passes – seat assignments per flight

tickets and ticket_flights – ticket and fare details

bookings – booking dates and total booking amounts

aircrafts_data and airports_data – aircraft and airport metadata

The database represents real-world airline operations and enables detailed occupancy and revenue analysis.

## 🛠️ Tools & Technologies

SQL – data extraction, joins, CTEs, aggregations

Python – data analysis and visualization

Pandas

Matplotlib

SQLite – local database for analysis

## 📊 Key Analysis Performed
1. Aircraft Capacity Analysis

Identified aircraft with more than 100 seats

Compared seating capacity across aircraft types

2. Booking & Revenue Trends

Analyzed how ticket bookings and total revenue change over time

Identified peak booking periods

3. Fare Class Pricing Analysis

Compared average ticket prices across fare classes (Business, Economy, Comfort)

Evaluated how pricing differs by aircraft type

4. Occupancy Rate Calculation

Calculated average occupancy rate per aircraft using boarding and seat data

Identified under-utilized aircraft with lower seat occupancy

5. Revenue Impact Simulation

Estimated the potential increase in annual revenue by assuming a 10% increase in occupancy rate

Highlighted how small improvements in seat utilization can significantly impact turnover

## 📈 Visualizations

Line charts showing booking and revenue trends over time

Bar charts comparing fare class pricing across aircraft

Occupancy rate comparison by aircraft

All visualizations were created using Python to clearly communicate insights.

## 🔍 Key Insights

Aircraft with lower ticket prices often achieved higher occupancy through volume.

Some aircraft types showed low occupancy and low revenue, indicating opportunities for pricing or operational adjustments.

A modest improvement in occupancy rate could lead to a substantial increase in annual revenue.

## 💡 Recommendations

Review pricing strategies for low-occupancy aircraft

Consider dynamic pricing to improve seat utilization

Focus on optimizing occupancy rather than increasing capacity

## 🚀 Conclusion

This project demonstrates how SQL and Python can be used together to analyze airline data, calculate occupancy rates, and estimate revenue improvements. The findings highlight the importance of efficient seat utilization and data-driven pricing strategies in improving airline profitability.
