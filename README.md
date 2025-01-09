# Predicting Industrial Machine Downtime: Level 1

## 📖 Project Overview

This project focuses on analyzing machine downtime for a high-precision manufacturing facility that produces components for aerospace, automotive, and medical device industries. The goal is to develop a data-driven approach to predictive maintenance by exploring operational data collected over a period of 7.5 months.

## 🎯 Project Objectives

- Analyze machine operational data
- Identify patterns in machine downtime
- Provide actionable recommendations for maintenance optimization

## 💾 Dataset Details

### Data Source
- File: `data/machine_downtime.csv`

### Key Columns
- Date
- Machine_ID
- Assembly_Line_No
- Various sensor measurements:
  - Hydraulic Pressure
  - Coolant Pressure
  - Air System Pressure
  - Temperature readings
  - Vibration measurements
  - Spindle Speed
  - Voltage
  - Torque
  - Cutting Force
- Downtime indicator

## 🔍 Key Findings

### 1. Data Collection Period
- **Start Date**: November 24, 2021
- **End Date**: July 3, 2022
- **Duration**: Approximately 7.5 months

### 2. Torque Analysis
- **Average Torque**: 25.23 Nm

### 3. Downtime Analysis
- **Most Affected Assembly Line**: Shopfloor-L1
- **Total Downtimes**: 1,265
- **Downtimes in Shopfloor-L1**: 454

## 📊 Visualizations

### Torque Distribution
![Torque Distribution](path/to/torque_distribution.png)

### Downtime per Assembly Line
![Downtime per Assembly Line](path/to/downtime_bar_chart.png)

## 🚀 Recommendations

1. **Prioritize Maintenance for Shopfloor-L1**
   - Conduct detailed machine inspections
   - Implement frequent preventive maintenance
   - Train operators on best practices

2. **Optimize Torque Levels**
   - Continuously monitor torque variations
   - Ensure operation within manufacturer-specified limits

3. **Expand Data Collection**
   - Continue gathering long-term data
   - Incorporate additional variables

4. **Implement Proactive Maintenance**
   - Utilize predictive analytics
   - Schedule maintenance during planned downtimes

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

## 📈 Future Work

- Develop predictive maintenance models
- Integrate more detailed maintenance logs
- Explore machine learning algorithms for downtime prediction

## 👥 Contributors
- [Hafida Bleayd]

## 📄 License
[Specify License - e.g., MIT, Apache 2.0]
