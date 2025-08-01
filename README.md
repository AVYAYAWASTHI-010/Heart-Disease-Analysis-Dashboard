# ❤️ Heart Disease Analysis Dashboard

An interactive Power BI dashboard designed to analyze **heart disease patient survival rates** based on clinical factors such as age, serum creatinine, ejection fraction, smoking, high blood pressure, diabetes, and anaemia.  
The dashboard provides insights into patient survival trends and risk factors to support healthcare decision-making.

---

## 📌 Short Description / Purpose
This dashboard helps analyze medical data to identify the impact of different health conditions and demographics on survival outcomes.  
It assists healthcare professionals, researchers, and students in understanding correlations between patient health indicators and survival rates.

---

## 🛠️ Tech Stack
- 📊 **Power BI Desktop** – Core platform for interactive dashboard development  
- 🔄 **Power Query** – For transforming and cleaning clinical dataset  
- 🧠 **DAX (Data Analysis Expressions)** – Used for survival rate calculations and visual measures  
- 📁 **.pbix File Format** – Saved project file for Power BI Desktop  
- 🖼️ **.jpg Screenshot** – Preview image for GitHub documentation  

---

## 📂 Data Source
Dataset: **Heart Failure Clinical Records** (UCI Repository / Kaggle)  
The dataset includes 299 patient records with attributes such as:  
- Age, Gender  
- Serum Creatinine, Ejection Fraction  
- Anaemia, Diabetes, High Blood Pressure, Smoking  
- Time (follow-up period), Death Event  

---

## ✨ Features / Highlights
### 🔹 Key Business Problem
Heart disease is one of the leading causes of death globally. Understanding the key factors affecting survival can improve patient monitoring and treatment strategies.  

### 🔹 Dashboard Goals
- Visualize **overall survival rate** and **average age of survival**  
- Analyze **survival trends by age group**  
- Compare **serum creatinine & ejection fraction with survival counts**  
- Assess the **impact of comorbidities** (smoking, hypertension, diabetes, anaemia)  
- Provide quick KPIs for total survival and deaths  

### 🔹 Walkthrough of Key Visuals
- **Survival KPIs** → Displays overall survival rate, average survival age, total survival, and total deaths  
- **Survival Count by Age Group** → Relationship between survival count and serum creatinine levels  
- **Ejection Fraction Analysis** → Survival count vs. ejection fraction by age  
- **Survival Rate by Age Group (Line Chart)** → Clear trend of declining survival rate with increasing age  
- **Comorbidity Impact (Stacked Area Chart)** → Visualizes influence of smoking, high BP, diabetes, and anaemia across age groups  

### 🔹 Insights & Impact
- Younger patients (<40) show **100% survival rate**  
- Survival rates drop significantly with **increasing age**  
- High serum creatinine and low ejection fraction are strong indicators of **lower survival probability**  
- Comorbidities like diabetes, smoking, and hypertension further reduce survival chances  

---

## 📸 Screenshots / Demos
### Dashboard Preview
![Heart Disease Dashboard](Heart%20Disease%20Dashboard.jpg)

---

## 🚀 How to Use
1. Download or clone this repository  
2. Open `Heart_Disease_Dashboard.pbix` in **Power BI Desktop**  
3. Refresh the dataset to view updated insights  
4. Use slicers (gender/age group) for interactive analysis  

---

## 📬 Contact
For questions, feedback, or collaboration:  
👉 Open an issue on GitHub or reach out via email.  
