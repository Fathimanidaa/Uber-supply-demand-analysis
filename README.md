# 🚕 Uber Supply-Demand Gap Analysis

This project is an Exploratory Data Analysis (EDA) of Uber ride request data. The goal is to identify patterns of ride cancellations and unavailability, understand the mismatch between supply and demand, and suggest actionable insights to improve service efficiency.

---
## 🎯 Objective

To analyze Uber ride requests and identify:

- Time slots and hours with high cancellation or unavailability
- Pickup locations (City vs Airport) with supply-demand issues
- Peak demand hours
- Suggestions for reducing failed rides

---

## 📊 Tools & Techniques Used

- **Microsoft Excel**  
  - Data Cleaning & Time Column Extraction  
  - Pivot Tables for aggregation  
  - Charts: Stacked Column, 100% Bar, Line Chart  
  - Dashboard design with text observations
 **Google Colab (for EDA using Python – Pandas)** 
  - **GitHub (for publishing)**
 
  - ## 📌 Key Insights

### 📌 1. Status by Time Slot:
- **Night** and **Early Morning** have the highest failure rates.
- **Night**: ~1300 trips failed due to **No Cars Available**
- **Early Morning**: Almost equal number of **Cancellations** and **No Cars**

### 📌 2. Pickup Point Patterns:
- **Airport** → Mostly failed due to **No Cars Available** (~1700)
- **City** → Mostly failed due to **Cancellations** (~1066)

### 📌 3. Hourly Demand:
- Peak request hours are between **5–9 AM** and **5–9 PM**
- These align with office commute hours

---# 📝 Observation Summary (Added in Dashboard)

> **Observation:**  
> The data shows a clear mismatch between Uber’s ride demand and supply during Night and Early Morning time slots. Airport pickup issues are driven by unavailability of cars, while City cancellations are due to driver behavior. Recommendations include incentivizing night-time drivers and managing cancellations more effectively.

---

## ✍️ Author

- 👤 **Nida Fathima**  
- 📘 Beginner Data Analyst | Exploring real-world datasets  
- 🌐 GitHub: [your-github-profile-link]

- 
