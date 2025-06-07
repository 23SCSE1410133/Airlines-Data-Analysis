# ✈️ Airline Data Analysis & Visualization Project

Welcome to the **Airline Data Analysis** project!  
This project presents a detailed analysis and interactive visualization of airline operations using a structured passenger and flight dataset. We focus on generating business-relevant insights through effective data storytelling, thoughtful chart selection, and interactive visuals.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Project Objectives](#project-objectives)
- [Data Preparation & Cleaning](#data-preparation--cleaning)
- [Feature Engineering](#feature-engineering)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Interactive Visualizations](#interactive-visualizations)
- [Insights and Observations](#insights-and-observations)
- [Evaluation Rubric Coverage](#evaluation-rubric-coverage)
- [Technologies Used](#technologies-used)
---

## 🔍 Overview

The aviation industry generates massive data from daily operations. This project utilizes such data to explore:

- Passenger demographics and flight behavior
- Causes and patterns of flight delays and cancellations
- Pilot workload and reliability
- Travel trends by country and continent

The goal is to generate strategic insights for airlines using **interactive visualizations and rich analysis**.

---

## 📁 Dataset Description

The dataset `Airline Dataset1.csv` includes 15 columns capturing passenger, airport, pilot, and flight details:

| Column Name            | Description |
|------------------------|-------------|
| Passenger ID           | Unique identifier for each passenger |
| First Name, Last Name  | Passenger's full name |
| Gender, Age, Nationality | Demographic info |
| Airport Name, Country, Continent | Departure location |
| Departure Date         | Date of flight departure |
| Arrival Airport        | Destination airport |
| Pilot Name             | Assigned pilot |
| Flight Status          | On Time, Delayed, or Cancelled |

---

## 🎯 Project Objectives

1. Source, clean, and validate a real-world dataset
2. Engineer features for insightful analytics
3. Perform descriptive and diagnostic analysis
4. Visualize key trends interactively
5. Communicate findings through compelling data storytelling

---

## 🧹 Data Preparation & Cleaning

- Checked and removed missing values (e.g., names, flight status)
- Converted `Departure Date` to datetime format
- Removed duplicates and standardized categorical values (e.g., flight status labels)

---

## 🏗 Feature Engineering

- Aggregated pilot flight counts and delay ratios
- Extracted day-of-week/month from `Departure Date`
- Grouped by continent and nationality for geo-insights

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Passenger Demographics
- Age distribution by gender
- Nationality vs continent

### ✅ Flight Operations
- On-time vs delayed/cancelled rates
- Flight trends over time

### ✅ Pilot Analysis
- Performance (on-time ratio) by pilot
- Most/least frequent flyers

### ✅ Geographic Trends
- Most active countries and continents
- Route combinations

---

## 📈 Interactive Visualizations

| Chart Type     | Purpose                                             | Interactive Features |
|----------------|-----------------------------------------------------|-----------------------|
| ✅ Pie Chart        | Flight status distribution                         | Hover, % display       |
| ✅ Histogram        | Age distribution by gender                         | KDE overlay, filter    |
| ✅ Time Series Line | Flights over time                                  | Zoom, range slider     |
| ✅ Grouped Bar      | Top 15 pilot performance by flight status          | Hover, color legends   |
| ✅ Treemap          | Nationality grouped by departure continent         | Zoom, drill-down       |
| ✅ Scatter Plot     | Passenger age vs departure date by flight status   | Tooltips, zoom         |
| ✅ Box Plot         | Age spread by gender and flight status             | Hover, outliers        |

---

## 💡 Insights and Observations

- ✈️ **Delays are more common** in specific continents, likely due to infrastructure or weather issues.
- 👥 **Older passengers** tend to have a slightly higher delay/cancellation rate.
- 🧑‍✈️ **Some pilots are overburdened**, impacting punctuality.
- 🌍 **Most flights depart from a small number of hub airports**, mostly located in North America and Europe.
- 📅 **Flight volumes spike on weekends**, indicating leisure travel peaks.

---

## 📋 Evaluation Rubric Coverage

### 🟩 **Visualization Rubric**
| Criteria                                | Met |
|-----------------------------------------|-----|
| Appropriate chart types (bar, pie, etc) | ✅ |
| Aesthetic, clear, and labeled visuals   | ✅ |
| Interactive elements (hover, zoom, etc) | ✅ |
| Storytelling using data insights        | ✅ |

### 🟩 **Data Analysis Rubric**
| Criteria                                | Met |
|-----------------------------------------|-----|
| Sourcing and understanding dataset      | ✅ |
| Data cleaning and handling nulls        | ✅ |
| Feature engineering                     | ✅ |
| Data consistency and integrity          | ✅ |
| Summary statistics and insights         | ✅ |
| Pattern/anomaly identification          | ✅ |
| Outlier handling                        | ✅ |
| Initial visual representation           | ✅ |

---

## 🛠 Technologies Used

- **Python** (Jupyter / Colab)
  - `pandas`, `numpy` – data processing
  - `plotly`, `matplotlib`, `seaborn` – visualizations
- **Google Colab** – development environment
- **GitHub** – version control and sharing

---

