# Real Estate Marketing Behavior Analysis  
**A Python-based data analysis project examining how scarcity and urgency cues influence consumer purchase intention.**

## 📌 Overview  
This project analyzes survey data related to real estate marketing messages to understand how psychological triggers—specifically **scarcity** and **urgency**—shape consumer decision-making. The analysis includes data cleaning, reliability testing, descriptive statistics, correlation analysis, predictive modeling, and hypothesis testing.

---

## 📂 Project Workflow  

### 1️⃣ Data Loading  
- Importing the dataset (Excel/CSV) into Python using Pandas.  
- Inspecting structure, column names, and response patterns.  

### 2️⃣ Data Cleaning  
- Removing unnecessary columns (e.g., Timestamp).  
- Handling duplicates.  
- Encoding Likert-scale responses (1–5), Gender, Yes/No fields, and Education levels.  
- Renaming long survey items into meaningful labels.  
- Grouping items into 3 constructs:  
  - **Scarcity Messaging**  
  - **Perceived Urgency**  
  - **Purchase Intention**

---

## 📊 Descriptive Statistics  
- Calculating means, standard deviation, min/max, and distribution patterns for each group.  
- Generating summary tables to understand central tendencies and variability.

---

## 🔗 Correlation Analysis  
### **Group-Level Correlation**  
- Positive correlations between:  
  - Scarcity ↔ Urgency  
  - Scarcity ↔ Intention  
  - Urgency ↔ Intention  
- Strongest correlation found between **Urgency and Purchase Intention**.

### **Item-Level Correlation**  
- High internal correlations within each construct (0.81–0.83).  
- Demographics (Age, Gender, Education) show weak correlations → minimal demographic influence.

---

## 🧪 Reliability Testing (Cronbach’s Alpha)  
All three constructs show **α > 0.70**, confirming strong internal consistency.

- Scarcity: High reliability  
- Urgency: High reliability  
- Intention: High reliability  

A visualized bar chart highlights the alpha values for all groups.

---

## 🤖 Regression Analysis  
Models applied:

- **Linear Regression**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**

**Performance:**  
- Linear Regression: R² = **0.56**  
- Ensemble models used for comparison and improved predictive insights.

**Goal:** Predicting Purchase Intention using Scarcity, Urgency, and demographics.

---

## 🧪 Validity Testing  
### **Construct Validity**  
- Scarcity ↔ Urgency: 0.46  
- Scarcity ↔ Intention: 0.53  
- Urgency ↔ Intention: 0.67  
→ Shows convergent + discriminant validity.

### **Predictive Validity**  
- Purchase Intention predicted moderately well by the regression model.

### **Group Comparison (t-test)**  
- Male vs Female intention: **No significant difference** (p = 0.479).  
→ Gender does not affect intention.

---

## 🔬 ANOVA  
- Testing Intention across education levels.  
- Result: **No significant difference** (p > 0.05).  
- Interpretation: Education does not influence perception of scarcity/urgency messaging.

---

## 📈 Visualizations  
- **Reliability bar charts**  
- **Divergent bar charts** for Likert items  
- **Heatmap** for correlations  
- **Histogram** for age distribution  
- **Gender bar chart**  
- **Boxplots** for Scarcity / Urgency / Intention  
Each visualization helps understand how participants perceive marketing cues.

---

## 🏁 Conclusion  
- **Scarcity and urgency cues strongly increase purchase intention.**  
- **Demographics have minimal influence**, making the messaging effective across groups.  
- **Constructs show high reliability and validity**, supporting the strength of the measurement model.

---

## 💡 Recommendations  
- Highlight **limited-time offers** and **exclusive opportunities**.  
- Apply scarcity/urgency messaging consistently across marketing channels.  
- Continuously refine message wording based on item-level feedback.

---

## 🛠️ Technologies Used  
- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Statsmodels  

---

## 📎 Files  
- `cleaned_practice_dataset_240_modified_v3.csv`  
- `notebook.ipynb`  
- `presentation.pptx`  
- `README.md` (this file)

---

## 🙌 Author  
**Farah Osama**  
Data Analyst | Machine Learning Enthusiast  

---

