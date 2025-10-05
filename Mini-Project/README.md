
# Smart Traffic Flow Optimization using Big Data (PySpark)

## Overview
This project analyzes real-time traffic flow data to identify congestion hotspots, optimize vehicle movement, and reduce accidents using Big Data analytics (PySpark).

## Dataset
- **File**: smart_traffic_data.csv
- **Rows**: 1000
- **Columns**: Location, TimeSlot, VehicleType, VehicleCount, AvgSpeed(kmph), Weather, AccidentsReported

## Steps Performed
- Data Cleaning & Loading
- Aggregations with PySpark (average speed, total vehicles, accident hotspots)
- Actionable Insights & Recommendations

## Tools Used
- Python (PySpark, Pandas)
- Jupyter Notebook / VS Code
- Matplotlib, Seaborn for visualization

## How to Run
```bash
spark-submit pyspark_traffic.py
```
