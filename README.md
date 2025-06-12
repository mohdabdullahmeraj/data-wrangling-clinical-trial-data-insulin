# 📊 Data Wrangling: Clinical Trial Data for New Oral Insulin (Auralin)

## 🧪 Project Overview

This project focuses on the **data wrangling** process for a **phase two clinical trial** involving a new oral insulin drug named **Auralin**. The trial investigates the drug’s efficacy, dose response, and short-term side effects in patients with elevated HbA1c levels.

Data wrangling—also known as data munging—is the essential step of assessing, structuring, and cleaning raw data into a format suitable for analysis and decision-making. As datasets become larger and more unstructured, effective wrangling is a critical skill in any data-related field.

---

## 📁 About the Dataset

### 🔬 Background

- **Diabetes** is a growing global health issue. Before the 1920s, it was nearly always fatal. 
- The discovery of **insulin** by Frederick Banting changed this, but insulin administration through injections remains the standard—often painful and inconvenient.

### 💊 The Study

This project analyzes data from a **clinical trial** exploring a promising **oral insulin** alternative—**Auralin**. The proprietary capsule is designed to overcome the key hurdle of oral insulin delivery: the stomach’s thick lining.

### 👥 Participants

- **Total Patients**: 350  
- All patients:
  - Were experiencing elevated **HbA1c** levels.
  - Had never used **Auralin** or **Novodra** as their primary insulin.
- Trial Design:
  - **Week 0–4**: All patients were administered **Novodra** to establish baseline HbA1c and insulin dose.
  - **Week 5–28**:
    - 175 patients continued with **Novodra**.
    - 175 patients switched to **Auralin**.

---

## 🔧 Project Steps

1. **Data Gathering**  
   Collected clinical trial data from provided `.csv` files.

2. **Data Assessment**  
   Checked for:
   - Quality issues (e.g., missing data, inconsistent formats)
   - Tidiness issues (e.g., incorrect structure, combined variables)

3. **Data Cleaning**  
   Applied various techniques to:
   - Correct errors and inconsistencies
   - Restructure messy or combined data
   - Handle null or unusual values

---

## 📌 Goal

To prepare the clinical trial data for analysis by transforming it into a clean, structured, and usable format that enables:
- Comparative evaluation of **Auralin** vs **Novodra**
- Identification of adverse reactions
- Insights into dose-response relationships and treatment efficacy

---

## 💡 Tools Used

- **Python (pandas, numpy)**
- **Jupyter Notebook**
- CSV files for data input

---

## ✅ Outcome

The cleaned dataset will enable further exploration of:
- HbA1c level changes
- Adverse reactions
- Potential of Auralin as a viable oral insulin therapy

---