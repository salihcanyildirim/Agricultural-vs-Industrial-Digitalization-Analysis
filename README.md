# Comparative Analysis of Digitalization: Agriculture vs. Industry (Machine Learning)

### Project Overview
This project applies **Machine Learning algorithms** to analyze and compare the digitalization levels of **Agricultural** and **Industrial** sectors in Turkey over a 23-year period (2000-2023).

The study aims to determine which structural factors (e.g., CO2 emissions, employment, high-tech exports) are the primary drivers of digitalization in each sector and to classify them using predictive modeling.

### Files in this Repository
* **`guncel_tez_kod_sec2ml.ipynb`**: The main **Python source code** containing data preprocessing, model training (Logistic Regression & Random Forest), and evaluation metrics.
* **`tez_sunum.pptx.pdf`**: The **Analysis Report & Presentation** summarizing the methodology and results.
* **`veri_seti_sec2ml.xlsx - Sayfa1.csv`**: The dataset used for training and testing the models (Sources: World Bank & TurkStat).

---

### Methodology & Tech Stack
**Libraries:** `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`

1.  **Data Preprocessing:**
    * Handled missing values and normalized the dataset using **MinMaxScaler**.
    * Addressed the **Imbalanced Data** problem (Agriculture vs. Industry sample sizes).
2.  **Modeling:**
    * **Logistic Regression:** Used for baseline classification and interpretation of coefficients.
    * **Random Forest Classifier:** Applied to handle non-linear relationships and improve accuracy on the minority class (Agriculture).
3.  **Evaluation:**
    * **Confusion Matrix:** To visualize true/false positives.
    * **Feature Importance Analysis:** To identify key drivers of digitalization.

---

### Key Findings
* **Random Forest** outperformed Logistic Regression in handling the imbalanced dataset, specifically improving the classification of the Agricultural sector.
* **Industrial Digitalization** is strongly correlated with *High-Tech Exports* and *Energy-based CO2 Emissions*.
* **Agricultural Digitalization** shows a more traditional structure, heavily dependent on *Fertilizer Consumption* and *Employment Rates*.

---

### Author
**Salih Can Yıldırım**
*Management Information Systems Graduate | Data Analyst Candidate*
