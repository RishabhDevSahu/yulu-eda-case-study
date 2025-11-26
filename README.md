# 🚲 Yulu Demand Analysis — Hypothesis Testing & Statistical Modeling

## 🎯 Overview
This project explores factors affecting demand for shared electric bicycles using hypothesis testing and statistical analysis techniques.  
The goal is to identify key variables influencing rentals and use these findings to help **Yulu improve operations, demand forecasting, and marketing strategy.**

---

## 🧩 Problem Statement

Yulu aims to understand why demand is fluctuating and which factors significantly influence bicycle rentals.

### Objectives:
- Identify key variables affecting demand.
- Measure how strongly these variables correlate with rental patterns.
- Validate findings using hypothesis testing and statistical modeling.

### Analysis Focus Areas:
- 🌤 **Weather Conditions**
- ⏰ **Time of Day**
- 🧑‍🤝‍🧑 **User Demographics**
- 📍 **Station Proximity**
- 📅 **Working vs Non-Working Days**

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| 🧾 Pandas | Data processing & cleaning |
| 🧮 NumPy | Numerical/statistical computation |
| 📈 SciPy (stats module) | Hypothesis testing (T-test, ANOVA, Chi-square, normality tests) |
| 📊 Statsmodels | Advanced statistical modeling & hypothesis evaluation |
| 🎨 Seaborn | Analytical plotting & statistical visualization |
| 📊 Matplotlib | Custom graphs & visual summaries |

---

## 🔍 Key Insights

### 1️⃣ Data Characteristics
- The dataset contains **both numerical (temp, humidity, rentals)** and **categorical variables (weather, season, user type)**.
- No missing values — ensuring **high reliability and clean statistical processing.**

---

### 2️⃣ Usage & User Behavior
- Registered vs casual users exhibit **different usage patterns**, indicating diverse motivations.
- Rentals show **consistent engagement**, regardless of day type (weekend vs weekday).

---

### 3️⃣ Environmental Influence
- Rentals **significantly increase on clear weather days.**
- Seasonal trends show highest rentals during **Summer and Fall**, indicating cycling preference in pleasant climates.

---

### 4️⃣ Hypothesis Test Results
- **T-Test:** No statistically significant difference between rentals on working vs non-working days → demand remains steady.
- **ANOVA:** Strong evidence that weather and season significantly affect rental volume.
- **Chi-Square:** Weather and season are dependent → predictable pairing useful for planning.
- **Normality Testing:** Skewed data → non-parametric or corrected methods may be required.

> 📌 Conclusion: **Environmental and temporal variables significantly impact demand — user type and weather contribute the strongest signals.**

---

## 📈 Summary

The analysis shows that **weather, seasonality, and user category** are major drivers of Yulu rental demand. Business optimization should consider time-based patterns, operational adjustments, and targeted promotions.

---

## ✅ Recommendations

| Strategy Area | Action |
|--------------|--------|
| 🛴 Fleet Optimization | Adjust bicycle inventory based on hourly, seasonal, and weather-driven demand |
| ☀ Seasonal Campaigns | Promote heavily during Summer and Fall when rentals peak |
| 🌤 Weather-Responsive Ads | Push real-time app offers on clear days to maximize usage |
| 💸 Targeted Discounts | Offer lower rental rates on non-working days to incentivize casual riders |
| 👑 User Segment Strategy | Tailor promotions differently for **casual vs registered** users |
| 🔧 Maintenance Scheduling | Prioritize timely servicing during high-demand seasons |
| 📲 Digital Enhancement | Introduce a smoother app experience with real-time bike availability |
| 🗺 Smart Allocation | Allocate bikes geographically based on demand clusters |
| 🧥 Weather Education | Provide guidance or accessory suggestions for non-ideal weather riding |

---

## 🚀 Future Enhancements

- Demand forecasting using **time-series modeling**
- Machine learning classification for **user behavior prediction**
- Live demand notifications based on real-time environmental data

---

## 📚 Conclusion

This study highlights that external environmental factors and user types strongly influence rental demand.  
Using statistical evidence from hypothesis testing, Yulu can:

- Improve service availability  
- Optimize marketing strategy  
- Enhance operational efficiency  
- Reverse revenue decline through data-driven actions  

---

## 📜 License
This project is open-source and intended for educational and analytical research purposes.

---

⭐ *If you found this project helpful, consider starring the repository!*
