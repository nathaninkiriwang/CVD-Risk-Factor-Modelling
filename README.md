
# 🩺 CardioRisk-Analysis-Australia  
**Investigating Cardiovascular Risk Factors in Migrants and Non-Migrants using Data Science**  

## 📌 Overview  
Cardiovascular disease (CVD) remains a leading cause of mortality in Australia. This project analyzes **dietary and lifestyle influences on cholesterol levels and hypertension risk**, particularly comparing **migrants vs. native-born Australians**.  

Using data from the **Australian National Health Survey**, we employ **linear mixed models** to investigate:
- How diet affects **LDL/HDL cholesterol ratios**
- How lifestyle choices like **smoking, alcohol consumption, and exercise** influence **blood pressure**
- Whether **migration status** modifies these relationships

The study provides valuable **statistical insights** into how lifestyle interventions can be tailored to reduce CVD risk across different populations.

---

## 🔬 Key Findings  
✅ Higher **fruit consumption** was linked to lower **LDL cholesterol** in migrants, but had no effect in native Australians.  
✅ **Smoking** increased **hypertension risk** more significantly in native Australians compared to migrants.  
✅ **Exercise was more protective** for migrants than non-migrants in reducing systolic blood pressure.  
✅ No significant difference in **alcohol's impact** on cholesterol between groups.  

---

## 🛠 Methods & Techniques  
- **Data Preprocessing & Cleaning:** Handling missing values, categorical transformations  
- **Statistical Modeling:**  
  - **Censored Data Transformation** (LDL & HDL bins → continuous values)  
  - **Linear Mixed Effects Models** (random effects for age, interaction effects with migration status)  
  - **Interaction Analysis** (diet, lifestyle × migration status)  
- **Visualization:** Data trends, interaction plots, and cholesterol impact graphs  


