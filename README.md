# 🩺 Ulcer Health Risk Analysis (

## 📌 Project Overview
The **Ulcer Health Risk Analysis** project is a guided Power BI data analytics project focused on understanding **health, behavioral, and clinical factors** associated with ulcer severity and outcomes.

This project explores how patient demographics, lifestyle habits, medical history, and treatment patterns relate to ulcer stages, pain severity, and hospitalization outcomes. The dashboard is designed to support **healthcare insight generation and risk assessment** through interactive visuals and slicers.

> 📚 *This project was completed as a guided learning project under the mentorship of **Emmanuel Isaac** via YouTube. Full credit and appreciation for the guidance provided.*

---

## 🎯 Objectives
- Analyze patient-level ulcer risk factors and outcomes  
- Identify patterns across age, ulcer history, pain severity, and medication use  
- Create an **interactive and visually intuitive dashboard** for health insights  
- Strengthen hands-on Power BI skills using real-world healthcare scenarios  

---

## 🗂️ Datasets Used

### 1️⃣ Ulcer Dataset
This table contains patient-level clinical and lifestyle data.

**Columns:**
- `patient_id`
- `age`
- `sex`
- `bmi`
- `h_pylori_status`
- `ulcer_history`
- `med_type`
- `med_duration (Monthly)`
- `smoking_status`
- `alcohol_intake_level`
- `pain_severity`
- `pain_pattern`
- `gi_symptoms`
- `bleeding_symptoms`
- `ulcer_size_mm`
- `ulcer_depth`
- `hemoglobin_g_dl`
- `stool_ob`
- `ulcer_stage`
- `treatment_category`
- `hospitalization_required`
- `ulcer_outcome`
- `Date of Diagnosis`

---

### 2️⃣ Ulcer Image Dataset
This supporting table enhances visualization and user interaction.

**Columns:**
- `Ulcer_stage`
- `Image_Url`
- `Icon_Url`

This dataset is used to dynamically display **ulcer stage images** based on slicer selection.

---

## 🧮 Data Preparation & Feature Engineering
- Created a new **Age Group** column for demographic analysis  
- Developed DAX measures for:
  - **Average Age vs Overall Average**
  - **Average Ulcer Size vs Overall Average**
  - **Average Pain Severity vs Overall Average**
- Ensured clean, analysis-ready data with consistent formatting  

---

## 📊 Dashboard Features & Visuals

The Power BI dashboard includes the following key components:

### 🔢 KPI Cards
- Total patients/ Average Age (vs overall average)
- Average BMI/Average Ulcer Size (vs overall average)
- Average hemoglobin level/Average Pain Severity (vs overall average)

---

### 📈 Visualizations
- **Donut Chart** → Ulcer History Distribution  
- **Line Chart** → Age Distribution of Patients  
- **Stacked Bar Chart** → Prevalence of Ulcer Depth Levels  
- **Stacked Bar Chart** → Pain Pattern Distribution  
- **Stacked Column Chart** → Patient Distribution Across Medication Types  

---

### 🖼️ Interactive Image Visual
- An **image visual controlled by slicers** that dynamically displays ulcer stage images  
- Enhances storytelling and improves dashboard intuitiveness  

---

### 🎛️ Interactivity
- **Chiclet Slicers** for intuitive filtering by ulcer stage and related attributes  
- Seamless interaction across all visuals for exploratory analysis  

---

## 💡 Key Insights
- Certain age groups and prior ulcer history show higher ulcer severity patterns  
- Pain severity and ulcer depth are strongly associated with hospitalization needs  
- Medication types vary significantly across ulcer stages  
- Visual storytelling (images + slicers) improves interpretability of clinical data  

---

## 🛠️ Tools & Skills Applied
- **Power BI**
- DAX Measures & Calculations
- Data Modeling
- Healthcare Data Analysis
- Interactive Dashboard Design
- Analytical Storytelling

---

## 🙏 Acknowledgment
This project was guided by **Emmanuel Isaac** through a YouTube tutorial series.  
The guidance provided was instrumental in understanding Power BI features such as **chiclet slicers, KPI comparisons, and interactive visuals**.

---
## 📸Dashboard Preview

![](https://github.com/Lucky-ogolo/Ulcer-Health-Risk-Analysis/blob/2550b6541740376eedce8ce55f9a206a679a9be2/Screenshot%202026-02-06%20060510.png)

![](https://github.com/Lucky-ogolo/Ulcer-Health-Risk-Analysis/blob/2550b6541740376eedce8ce55f9a206a679a9be2/Screenshot%202026-02-06%20060605.png)
## 📎 Notes
This project is part of my **learning and portfolio development journey**.  
While guided, all implementation, exploration, and documentation were completed independently to reinforce practical understanding.

---
## 🤝 Let’s Connect
   📬 Author 
Ogolo lucky -  Data Analyst  
  - 💼 🔗[LinkedIn](www.linkedin.com/in/lucky-ogolo/)
  - 📧 🔗[Email](luuckyyyy@gmail.com) 

📬 *Feedback and suggestions are always welcome!*
