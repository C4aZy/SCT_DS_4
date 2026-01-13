# US Accidents Data Analysis (EDA)

## 📌 Overview

This project performs **exploratory data analysis (EDA)** on a large-scale **US Accidents dataset** to understand patterns related to **time, day, severity, weather conditions, and geographic distribution** of road accidents. Visualizations are used extensively to highlight trends and risk factors.

---

## 📊 Visualizations & Insights

### 1️⃣ Accidents by Hour of Day

**Objective:** Identify peak accident hours.

**Key Insights:**

* Accidents peak during **morning (7–9 AM)** and **evening (4–6 PM)** hours.
* These peaks align with **office commute times**.
* Lowest accident frequency occurs during **late night / early morning hours (1–4 AM)**.

📌 *Conclusion:* Traffic congestion and rush hours significantly increase accident likelihood.

---

### 2️⃣ Accidents by Day of Week

**Objective:** Analyze accident distribution across weekdays and weekends.

**Key Insights:**

* **Friday** has the highest number of accidents.
* **Weekdays** show consistently higher accident counts compared to weekends.
* **Sunday** records the lowest number of accidents.

📌 *Conclusion:* Work-related travel contributes more to accidents than leisure travel.

---

### 3️⃣ Accident Severity Distribution

**Objective:** Understand how severe accidents typically are.

**Severity Levels:**

* 1 → Least severe
* 4 → Most severe

**Key Insights:**

* **Severity 2** accidents dominate the dataset.
* Severe accidents (**Severity 3 & 4**) are relatively rare.
* Minor accidents occur far more frequently than fatal ones.

📌 *Conclusion:* Most accidents cause moderate disruption rather than extreme damage.

---

### 4️⃣ Top 10 Weather Conditions During Accidents

**Objective:** Examine the impact of weather on accidents.

**Key Insights:**

* Majority of accidents occur during **Fair** weather conditions.
* **Cloudy** and **Mostly Cloudy** conditions follow next.
* Adverse weather like **Fog, Snow, and Rain** accounts for fewer accidents overall.

📌 *Important Note:* Higher accident count in fair weather is due to **higher traffic volume**, not safer conditions.

---

### 5️⃣ Geographic Heatmap of Accidents (US Map)

**Objective:** Visualize accident density across locations.

**Key Insights:**

* High-density accident zones around **major cities and highways**.
* Coastal and urban regions show stronger clustering.
* Rural areas exhibit lower accident density.

📌 *Conclusion:* Urbanization and traffic density strongly influence accident frequency.

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas** – data manipulation
* **Matplotlib & Seaborn** – data visualization
* **Folium** – geographic heatmaps
* **Jupyter Notebook** – analysis environment

---

## 🎯 Key Takeaways

* Time, traffic volume, and location are major contributors to accidents.
* Weekdays and rush hours are higher risk periods.
* Most accidents are moderate in severity.
* Weather alone does not determine accident frequency.

---

## 🚀 Future Enhancements

* Predictive modeling for accident severity
* Correlation analysis between weather & severity
* City-level or state-level comparative analysis
* Time-series trend analysis

---

✅ This analysis provides actionable insights for **traffic planning, road safety policy, and risk mitigation strategies**.
