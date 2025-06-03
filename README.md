# 🧘‍♀️ Bellabeat Fitbit Data Analysis

This project explores and analyzes the Bellabeat Fitbit dataset to understand users' daily activity patterns and provide insights into their health and wellness behaviors.

---

## 📊 Project Objectives

- Perform **Exploratory Data Analysis (EDA)** on daily activity data
- Visualize key metrics such as **Calories**, **Steps**, **Activity Minutes**, and **Distance**
- Discover correlations between various physical activity factors
- Provide data-driven insights for better health recommendations

---

## 📁 Dataset Description

The main dataset used is:  
📂 `dailyActivity_merged.csv`  
It contains:

- `ActivityDate`: Date of the record  
- `TotalSteps`: Total steps taken  
- `TotalDistance`: Total distance covered  
- `VeryActiveDistance`, `ModeratelyActiveDistance`, `LightActiveDistance`: Distance breakdown by intensity  
- `VeryActiveMinutes`, `LightlyActiveMinutes`, etc.: Active minutes  
- `Calories`: Total calories burned  
- And more...

---

## 📌 Key Libraries Used

- `pandas` for data manipulation  
- `matplotlib` and `seaborn` for data visualization  
- `numpy` for numerical operations

---

## 📈 Visualizations Included

- Calories vs Steps (regression plot)
- Calories vs Distance types (Very Active, Moderate, Light)
- Daily trends of steps and calories
- Bar plots for average time spent in activity levels

---

## 🔧 How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
