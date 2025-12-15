Capstone Project: Logistic Regression Model for Birmingham, AL Housing Risk
🏠 Project Overview

This Capstone project, developed for the PSU MSADSB program, centered on building a scalable, data-driven system to accurately assess tenant default risk for a housing guarantee company. Our core contribution was integrating internal applicant data with external economic indicators to create a robust, interpretable risk model for the Birmingham, AL market.

---

✨ Key Technical Achievements

The following achievements detail the technical scope, methodology, and direct business impact of the project:

1.  **Built a core risk model** using an interpretable **Logistic Regression classifier (Scikit-learn)**. This model scores applicant default probability based on key financial predictors like Rent-to-Income and Credit Score. 
2.  **Sourced and managed a complex ETL pipeline** to unify applicant records with four disparate public data sets (including Census, Eviction Lab, and ACRE economic data) to create a predictive feature set.
3.  **Identified high-risk market segments** through localized analysis for Birmingham, AL. We quantified that **42% of local renters are severely rent-burdened** and pinpointed ZIP codes with the highest predicted default rate (**~7.2%**).
4.  **Drove policy change** by creating clear visualization reports (**Matplotlib/Seaborn**), which definitively showed the **30% Rent Burden threshold** as the most influential factor, guiding final client recommendations.

---

🛠️ Methodology and Approach

 Modeling Pipeline
The primary predictive tool was a Logistic Regression model, selected specifically for its interpretability in a high-stakes financial risk assessment context. The model relies on features engineered from our integrated data sources, including:
* Rent-to-Income Ratio (Rent Burden)
* Applicant Credit Score
* Local Economic Indicators (e.g., ZIP Code-level unemployment)

Key Finding: Rent Burden
The analysis confirmed that the **Rent-to-Income ratio (Rent Burden)** was the most significant predictor of tenant default, establishing the **30% threshold** as the critical point for risk-based policy recommendations.

---

📂 Repository Contents

This repository contains the full project lifecycle, from initial planning to final model deployment and reporting.

| File Name | Description | Category |
| :--- | :--- | :--- |
| `logistic regression model_Birmingham AL (1).ipynb` | **The final working Jupyter Notebook.** Contains the data cleaning, feature engineering, Logistic Regression model training, and evaluation. | **Code** |
| `logistic regression model _Birmingham_AL.docx` | **Model Summary Report.** Detailed documentation on the modeling process, evaluation, and feature insights. | **Documentation** |
| `Birmingham, AL – Research Insights_Manas (1).docx` | **Market Insights Report.** Contains the quantitative findings on localized market risk (e.g., 42% rent-burdened data). | **Documentation** |
| `OneApp Capstone '25 Draft.pptx` | The final Capstone Presentation slides. | **Report** |
| `sales_AL_cleaned (4).xlsx - Sheet1.csv` | The core sales and applicant data used to train the model. | **Data** |
| `application_jobIndustry (2) (1).csv` | Supplementary data used for advanced feature engineering. | **Data** |



 💻 Tech Stack

* **Language:** Python
* **Modeling:** Scikit-learn (Logistic Regression)
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Reporting:** Microsoft Word, PowerPoint
