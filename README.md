# 🏥 Healthcare Patient Analysis & Outcome Prediction


This project performs an in-depth analysis of hospital inpatient discharges using a large healthcare dataset from Kaggle. **It combines Exploratory Data Analysis (EDA), Statistical Analysis, Predictive Insights,** and an **interactive Power BI dashboard** to uncover hidden patterns in patient data, hospital costs, outcomes, and severity levels.

---
🔗 Dataset Source:
[CMS Hospital Inpatient Discharges - Kaggle](https://www.kaggle.com/datasets/bhautikmangukiya12/hospital-inpatient-discharges-dataset?select=Hospital_Inpatient_Discharges__SPARCS_De-Identified___2021_20231012.csv)

## 📌 Objectives

- Understand patient characteristics and admission patterns.
- Analyze how severity levels influence **Length of Stay (LOS)** and costs.
- Identify if admission types (Emergency, Elective) affect patient outcomes.
- Use statistical tests to validate hypotheses.
- Visualize insights with a compelling **Power BI storytelling dashboard**.

---

## 📂 Project Structure
``` Bash
📁 Healthcare-Patient-Analysis/ │
├── 📊 Health care analysis.pbix # Power BI Interactive Dashboard 
├── 📓 Healthcare Patient Analysis.ipynb # EDA + Inferential Stats in Python 
└── 📄 README.md # Project documentation
```


---

## 🧪 Data Source

Dataset used: **CMS Hospital Inpatient Discharges (SPARCS De-Identified Data)**

Includes details such as:

- Patient Age, Gender, Ethnicity
- Hospital Service Area, Facility
- Length of Stay, Admission Type, Disposition
- Severity, Mortality Risk
- Total Charges and Total Costs

---

## 📊 Exploratory Data Analysis (Python)

- ✅ Cleaned and preprocessed data.
- ✅ Performed **EDA** with seaborn, pandas & matplotlib.
- ✅ Analyzed relationships between cost, LOS, severity, and other patient demographics.
- ✅ Built correlation heatmaps and boxplots.

---

## 📈 Inferential Statistics

Statistical Tests performed:

| Test             | Objective                                                                             | Result             |
|------------------|----------------------------------------------------------------------------------------|--------------------|
| ✅ Chi-Square     | Relationship between Admission Type & Patient Disposition                             | Significant        |
| ✅ ANOVA          | Do different **Severity Levels** affect **LOS**?                                      | Significant        |
| ✅ T-Test         | Compare LOS between **Medical** and **Surgical** patients                              | Significant        |
| ✅ A/B Test       | Compare Total Charges between **Emergency** and **Elective** admissions                | Significant        |

📌 **All tests rejected the null hypothesis**, confirming meaningful differences in hospital outcomes.

---

## 📊 Power BI Dashboard Highlights

An interactive Power BI dashboard with:

### 1️⃣ Cover Page
- Project title, logos, navigation buttons with bookmarks.

### 2️⃣ Demographics
- Age-wise, gender, race, and county-level distribution.

### 3️⃣ Cost & Severity
- Total charges vs. total costs
- Severity impact on LOS and billing

### 4️⃣ Inferential Summary
- KPI cards for each test result.
- Text blocks explaining hypotheses and conclusions.

### 5️⃣ 📌 Recommendations
- Data-driven suggestions to improve healthcare delivery & cost efficiency.

---

## 💡 Key Insights

- Emergency admissions lead to significantly higher costs than elective ones.
- Higher severity levels correlate with increased LOS and expenses.
- Medical patients have longer stays compared to surgical ones.
- Counties and zip codes show distinct service patterns—useful for resource allocation.

---

## 📢 Recommendations

- **Optimize resource allocation** based on high-severity regions.
- Enhance **preventive care** to reduce emergency admissions.
- Monitor **length of stay patterns** to improve efficiency.
- Prioritize **cost reduction** strategies for high-risk patient groups.

---

## 📽️ How to Explore

1. Open `Health care analysis.pbix` in Power BI Desktop.
2. Run `Healthcare Patient Analysis.ipynb` to view EDA and statistical testing.
3. Navigate across dashboard pages using buttons/bookmarks.

---

## 🧰 Tools & Technologies
- Python (Jupyter Notebook) for data wrangling & inferential statistics
- Power BI for interactive data visualization and storytelling
- Pandas, Matplotlib, Seaborn, Scipy for data analysis
- Statistical Tests: Chi-Square, ANOVA, T-Test, A/B Testing


---

## 🤝 Contact

**Rakesh B.**  
Aspiring Data Scientist | MBA + Data Engineering Skills  
🔗 [LinkedIn](https://www.linkedin.com/) *(https://www.linkedin.com/in/rakesh-b-9b7709290/)*

---
## 🧠 Storytelling

The Power BI dashboard is structured to guide users through a data-driven story, starting with demographics and ending in actionable insights. It uses bookmarks, interactive visuals, and KPI cards to ensure that the narrative is easy to follow even for non-technical stakeholders.

The dataset is too large for GitHub, but can be downloaded from the [Kaggle source](https://www.kaggle.com/datasets/bhautikmangukiya12/hospital-inpatient-discharges-dataset?select=Hospital_Inpatient_Discharges__SPARCS_De-Identified___2021_20231012.csv)

⭐ If you found this project insightful, feel free to star ⭐ the repo or connect!

