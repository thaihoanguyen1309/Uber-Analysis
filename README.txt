# 🚗 Uber Operations & Customer Behavior Analysis (2024)

## 📌 Project Overview
This project analyzes the operational performance and customer retention of the **NCR Ride Bookings (Uber)** platform in 2024. Despite a massive scale of **148.8K rides** and **52 Billion in revenue**, the platform faced a critical challenge: high churn rates and a "One-and-Done" customer lifecycle.

The analysis focuses on identifying operational bottlenecks and segmenting users to develop high-impact retention strategies.

---

## ⚠️ Business Problem
Through initial EDA, three primary "Red Flags" were identified:
1. **Low Completion Rate:** Only **68.56%** of bookings were completed, resulting in over 31% loss in potential revenue due to cancellations.
2. **Retention Crisis:** A significant "One-and-Done" behavior where customer return rates at Month 1 (M1) were nearly 0.
3. **Negative Trend:** Retention rates showed a declining trend from Jan to Oct 2024, indicating a worsening user experience.

---

## 🛠️ Tech Stack & Methodology
* **Language:** Python (Pandas, NumPy, Matplotlib, Seaborn) for data cleaning and preprocessing.
* **Visualization:** Power BI for interactive dashboards and KPI tracking.
* **Analytical Frameworks:**
    * **RFM Analysis:** Segmenting 100k+ customers into actionable groups (Champions, Potential Loyalists, At Risk).
    * **Cohort Analysis:** Measuring time-based retention to identify exactly when and why customers churn.

---

## 🔍 Key Insights

### 1. The "Systemic" Churn
Analysis revealed that **38%** of unsuccessful trips were caused by system-level issues (App glitches, hidden pricing, or poor first-time experience), rather than driver performance. 

### 2. RFM Segmentation Results
* **Champions:** High-value core group, but small in volume.
* **Potential Loyalists:** The most active group recently (Recency ~11 days) but with low frequency—representing the biggest growth opportunity.
* **At Risk:** A large portion of users who abandoned the app after a single bad experience involving high freight costs.

### 3. The Retention "Death-Drop"
Cohort matrices proved that users didn't leave because of the vehicle type (Auto, Bike, or Sedan). Instead, they left because the platform failed to build a "second-ride habit."

---

## 🚀 Actionable Recommendations

* **"The Second Ride" Campaign:** Redirect marketing budget from first-ride acquisition to **massive discounts for the 2nd trip**. This aims to break the "One-and-Done" cycle and increase M1 retention.
* **Logistics Friction Mitigation:** Implement "Olist Prime" style features or subsidized shipping for high-value routes identified in the EDA "Red Zone."
* **Win-Back Surveys:** Deploy automated surveys to the **At Risk** segment immediately after a 1-star review or a failed booking to provide instant recovery vouchers.

---