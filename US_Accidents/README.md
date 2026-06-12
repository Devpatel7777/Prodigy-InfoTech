
# Road Safety Intelligence & Risk Analytics

## Project Overview

Road accidents are a major public safety concern that lead to injuries, traffic congestion, economic losses, and emergency response challenges.

This project analyzes over **500,000 traffic accident records** from the United States to identify patterns related to:

- Accident Severity
- Time of Day
- Weather Conditions
- Road Infrastructure
- Geographic Risk

The objective is to transform raw accident data into actionable road safety intelligence using data analytics and visualization techniques.

---

## Business Problem

Transportation authorities need data-driven insights to identify:

- High-risk accident locations
- Accident hotspots
- Dangerous road infrastructure
- High-risk states and cities
- Peak accident periods

This analysis helps prioritize road safety investments and improve transportation planning.

---

## Dataset Information

**Dataset:** US Accidents Dataset

**Records:** 500,000

**Features Include:**

- Severity
- Start Time
- End Time
- Weather Conditions
- Temperature
- Visibility
- Road Infrastructure Features
- Geographic Coordinates
- City
- State

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium
- Jupyter Notebook

---

## Data Preparation

### Data Cleaning

- Removed duplicate records
- Handled missing values
- Removed high-missing-value columns
- Fixed date and time formats

### Feature Engineering

Created new features:

- Duration_Minutes
- Hour
- Day
- Month

These features enabled deeper accident pattern analysis.

---

## Project Workflow

### 1. Severity Distribution Analysis

Analyzed accident severity levels to understand the distribution of accident impact.

### 2. Rush Hour Intelligence

Identified peak accident periods throughout the day.

### 3. Road Infrastructure Analysis

Evaluated the effect of:

- Junctions
- Traffic Signals
- Crossings
- Stop Signs

on accident severity.

### 4. State Risk Index

Developed a custom Risk Index:

Risk Index = Accident Count × Average Severity

to identify high-risk states.

### 5. City Risk Index

Identified the most dangerous cities based on accident volume and severity.

### 6. Weather Analysis

Analyzed weather conditions associated with accident occurrence.

### 7. Duration Impact Analysis

Investigated accident duration and its relationship with severity.

### 8. Accident Hotspot Analysis

Visualized accident hotspots using geographic heatmaps.

---

## Key Findings

### Severity Analysis

- Nearly 80% of accidents belong to Severity Level 2.
- Moderate-severity accidents dominate the dataset.

### Time Analysis

- Accident frequency peaks during:
  - 7–8 AM
  - 4–5 PM
- Rush-hour traffic is a major contributor to accidents.

### Road Infrastructure Analysis

- Junction-related accidents exhibit the highest severity.
- Traffic signals, crossings, and stop signs are associated with lower accident severity.

### Geographic Risk Analysis

Top Risky States:

- California
- Florida
- Texas

Top Risky Cities:

- Miami
- Houston
- Los Angeles

### Duration Analysis

- Severity Level 4 accidents require the longest clearance times.
- Severe accidents create greater traffic disruption.

### Weather Analysis

- Most accidents occur during Fair, Mostly Cloudy, and Clear conditions.
- No strong evidence was found that weather alone significantly increases accident severity.

### Hotspot Analysis

- Accident hotspots are concentrated in major metropolitan regions and transportation corridors.

---

## Business Recommendations

1. Increase traffic monitoring during rush-hour periods.

2. Improve safety measures at major junctions.

3. Expand and maintain traffic control infrastructure.

4. Prioritize road safety investments in:

   - California
   - Florida
   - Texas

5. Implement targeted accident prevention programs in:

   - Miami
   - Houston
   - Los Angeles

6. Improve clearance processes for high-severity accidents.

7. Expand monitoring systems in accident hotspot regions.

8. Use Risk Index metrics for transportation planning and resource allocation.

---

## Results

The analysis successfully identified:

✅ High-risk states

✅ High-risk cities

✅ Dangerous road infrastructure

✅ Rush-hour accident patterns

✅ Accident hotspots

✅ Severity-related traffic impacts

---

## Conclusion

This project demonstrates how data analytics can transform large-scale accident records into actionable road safety intelligence.

The findings provide valuable insights that can support:

- Road safety planning
- Traffic management
- Infrastructure improvements
- Resource allocation
- Transportation policy decisions

---

## Author

**Dev Patel**

Data Analyst 
