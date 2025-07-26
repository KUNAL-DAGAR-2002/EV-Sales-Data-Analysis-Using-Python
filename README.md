# 🚗 Electric Vehicle Data Analysis Project

This project focuses on analyzing electric vehicle (EV) data to extract meaningful insights, identify trends, and build a recommendation system. The dataset, `FEV-data-Excel.xlsx`, includes various features like range, price, battery capacity, energy consumption, and performance metrics of EVs.

---

## 📌 **Project Objectives**
- Analyze EV specifications and identify patterns.
- Perform filtering and grouping based on user criteria.
- Detect outliers in energy consumption.
- Visualize the relationship between battery capacity and range.
- Build a recommendation class for EVs based on user input.
- Perform hypothesis testing to compare engine power between Tesla and Audi.
- Provide actionable insights and recommendations.

---

## 📊 **Dataset Overview**
The dataset contains the following key columns:
- **Car full name:** Make, model, and variant of the EV.
- **Minimal price (gross) [PLN]:** Minimum retail price.
- **Battery capacity [kWh]:** Energy storage capacity.
- **Range (WLTP) [km]:** Driving range on a full charge.
- **Mean - Energy consumption [kWh/100 km]:** Average energy usage.
- **Engine power [KM], Maximum speed [kph], Boot capacity [l], Acceleration [s], Maximum DC charging power [kW]**, and other technical specifications.

---

## ⚙ **Technologies & Tools**
- **Language:** Python  
- **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `SciPy`  
- **IDE:** Jupyter Notebook  

---

## 🧠 **Key Tasks**
### **Task 1: EV Filtering & Grouping**
- Filter EVs with:
  - Budget ≤ **350,000 PLN**
  - Range ≥ **400 km**
- Group results by manufacturer and calculate **average battery capacity per manufacturer**.

### **Task 2: Outlier Detection**
- Identify EVs with unusually high/low **energy consumption** using statistical techniques (e.g., IQR method).

### **Task 3: Battery Capacity vs Range**
- Create scatter plots and trend lines to visualize their relationship.
- Highlight insights on how battery size impacts range.

### **Task 4: EV Recommendation Class**
- A Python class that suggests the **top 3 EVs** based on:
  - User budget  
  - Desired range  
  - Minimum battery capacity

### **Task 5: Hypothesis Testing**
- Perform a **two-sample t-test** (`scipy.stats.ttest_ind`) to check if there is a significant difference in the average **Engine Power [KM]** between **Tesla** and **Audi**.
- Provide statistical insights and business implications.

---

## 🔍 **Insights & Recommendations**
- **Battery capacity** is strongly correlated with EV range.
- Some models exhibit **high energy consumption outliers**, suggesting efficiency concerns.
- **Tesla** generally has higher average engine power compared to Audi (validated via t-test).
- For customers with a budget under 350,000 PLN and long-range needs, certain mid-range EVs (highlighted in analysis) offer the best value.

---

## 📹 **Project Video**
A short video explaining the methodology, key findings, and recommendations can be accessed here:  
**(https://drive.google.com/file/d/154F55HvMHViJD6Z2DHll5iIYct_7A16w/view?usp=sharing)**

