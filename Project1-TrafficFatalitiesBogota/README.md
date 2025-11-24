# Project 1 – Traffic Fatalities in Bogotá

**Tool:** Power BI  
**Dataset Source:** https://datosabiertos.bogota.gov.co/dataset/mortalidad-por-accidentes-de-transito  
**Author:** Alejandro Guerrero

---

## 🎯 Project Objective
Analyze traffic-related fatalities in Bogotá to identify:

- Historical trends  
- High-risk localities  
- Vulnerable population groups  
- Most frequent types of fatal accidents  
- Critical times during the day and week  

The goal is to build a data-driven and actionable dashboard for public safety insights.

---

## 📊 Key Performance Indicators (KPIs)

- Total fatalities per year  
- Year-over-year percentage variation (YoY)  
- Fatalities by locality  
- Fatalities by type of accident  
- Fatalities by age group and gender  
- Day and hour with the highest number of fatal accidents  

---

## 🗺️ Suggested Visualizations

- **Line chart:** yearly trend of fatalities  
- **Map:** concentration of fatalities by locality  
- **Bar charts:** distribution by accident type and by age group  
- **Donut:** user type (pedestrian, cyclist, passenger, driver)  
- **Heatmap:** day of week vs hour of day  
- **Cards:** main KPIs (yearly total, YoY change, locality with highest fatalities)  

---

## 🔧 Power Query Transformations

- Handling missing or inconsistent values  
- Standardizing date formats  
- Creating a proper date/calendar table  
- Cleaning and normalizing text fields  
- Removing irrelevant columns  
- Preparing fact and dimension structure  

---

## 🧮 DAX Measures (examples)

- **Total Fatalities:**  
  `Total Fatalities = COUNTROWS('Fatalities')`
- **Fatalities Current Year**  
- **YoY Variation (%):**  
  Comparison between selected year and previous year  
- **Measures for age segmentation, gender distribution, and accident type**  

---

## 📝 Expected Insights

- Identification of the most dangerous localities  
- Hours and days with the highest risk  
- Demographic groups most affected  
- Types of accidents that result in the highest fatality rates  
- Potential recommendations for public policy and road safety interventions  

---

## 📁 Project Structure

