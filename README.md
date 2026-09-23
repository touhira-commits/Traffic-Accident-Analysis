# 🚦 Traffic Accident Analysis

## 📌 Project Overview

Traffic Accident Analysis is an Exploratory Data Analysis (EDA) project performed using Python. The project analyzes traffic accident records to identify useful patterns based on **time, location/area, severity, accident type, and vehicle type**.

The analysis includes data cleaning, statistical analysis, and visualization of major accident patterns.

## 🎯 Aim

To perform Exploratory Data Analysis (EDA) on a traffic accident dataset using Python and identify useful patterns based on time, location/area, severity, accident type, and vehicle type through data cleaning, analysis, and visualization.

## 📂 Dataset

**Dataset File:** `Traffic_Accident_Dataset.csv`

The dataset contains **5,200 accident records** and **6 fields**:

* Date
* Time
* Location/Area
* Accident Type
* Severity
* Vehicle Type

## 🎯 Objectives

1. Understand the structure of the Traffic Accident dataset.
2. Identify missing values and duplicate records.
3. Clean and convert date/time fields.
4. Analyze accidents by time and identify accident trends.
5. Identify accident-prone locations/areas.
6. Analyze accident severity distribution.
7. Analyze accidents by vehicle type and accident type.
8. Visualize important accident patterns using graphs.
9. Write key observations from the analysis.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔍 Data Cleaning

The dataset was checked for:

* Missing values
* Duplicate records
* Date and time information
* Dataset structure and data types

After cleaning:

* **Missing values:** 0
* **Duplicate records:** 0
* **Final dataset size:** 5,200 rows × 6 columns

## 📊 Analysis Performed

### ⏰ Accident Analysis by Time

The accidents were analyzed according to the hour of occurrence.

**Peak accident hour:** 16:00 (4 PM) with **252 accidents**.

### 📅 Monthly Accident Trend

Monthly accident counts were analyzed to understand accident patterns throughout the year.

### 📍 Accident Analysis by Area

The number of accidents was analyzed for different locations/areas.

The **Central** area recorded the highest number of accidents with **902 records**.

### ⚠️ Accident Severity Analysis

Severity categories were analyzed:

| Severity | Records |
| -------- | ------: |
| Minor    |   2,396 |
| Moderate |   1,690 |
| Severe   |     827 |
| Fatal    |     287 |

### 🚗 Vehicle Type Analysis

The accident records were analyzed according to vehicle type.

The **Car** category had the highest number of records with **2,120 accidents**.

### 💥 Accident Type Analysis

Different accident types were analyzed.

The most common accident type was **Collision**, with **1,998 records**.

## 📈 Visualizations

The project includes visualizations such as:

* Accident trend line chart
* Area-wise accident bar chart
* Severity distribution plot
* Accident analysis by time
* Accident analysis by vehicle type
* Accident analysis by accident type

## 📝 Key Observations

1. The dataset contains **5,200 traffic accident records** across six fields.
2. There are no missing values or duplicate records in the dataset.
3. The Central area has the highest number of recorded accidents.
4. Minor accidents are the most common severity category.
5. Cars are the most frequently recorded vehicle type.
6. Collision is the most common accident type.
7. The highest number of accidents occurs at **16:00 (4 PM)**.

## 📌 Conclusion

The Traffic Accident EDA project demonstrates how Python can be used to inspect, clean, analyze, and visualize accident data. The analysis identifies patterns across **time, location, severity, vehicle type, and accident type**.

The visualizations provide a clear summary of the major accident patterns in the dataset.

## 📁 Project Structure

```text
Traffic-accident/
│
├── Traffic_Accident_Dataset.csv
├── Traffic_Accident_Analysis.ipynb
├── Traffic_Accident_Analysis.pdf
└── README.md
```

## 👩‍💻 Project

**Project:** Traffic Accident Analysis
**Type:** Exploratory Data Analysis (EDA)
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## 🔗 GitHub Repository

https://github.com/touhira-commits/Traffic-accident
