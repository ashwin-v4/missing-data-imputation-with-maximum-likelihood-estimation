# Missing Data Imputation with Maximum Likelihood Estimation  

## 📌 Exploratory Analysis – Lab Assessment 2  

This project demonstrates how to handle missing data using **Maximum Likelihood Estimation (MLE)** on the **NHANES dataset (2015–2016)**.  

---

## 📂 File Structure  
- **Maximum_Likelihood_Estimation.ipynb** → Jupyter Notebook containing the full analysis and imputation process.  
- **NHANES.csv** → Raw dataset with missing values.  
- **NHANES_2015_2016_tidy_imputed.csv** → Cleaned and imputed dataset after applying MLE.  

---

## 🔎 Workflow  
1. **Load & Explore Data**  
   - Import the NHANES dataset.  
   - Perform exploratory data analysis (EDA) to identify missing values.  

2. **Imputation using Maximum Likelihood Estimation (MLE)**  
   - Apply statistical modeling for estimating missing values.  
   - Validate assumptions and distributions.  

3. **Save Final Dataset**  
   - Export the imputed data into a tidy CSV format.  

---

## ⚙️ Requirements  
Install the following Python libraries before running the notebook:  

```bash
pip install pyampute missingno
