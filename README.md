# Paisabazaar-Loan-Prediction

## 📌 Project Overview
This project predicts the **Credit Score** of individuals based on financial and demographic data.  
It was created as part of my project on **Paisabazaar-Loan-Prediction**.

We implemented multiple models, and finally selected **Gradient Boosting Classifier** as our best model.

## 📂 Repository Contents
- `Sample_ML_Submission_Template.ipynb` → Main Jupyter Notebook with all code & analysis  
- `gradient_boosting_model.pkl` → Saved ML model file  
- `columns_list.txt` → List of dataset feature columns used in training  
- `Paisabazaar.pptx` → Project presentation slides  
- `README.md` → Project documentation  

---

## 📊 Dataset
Due to file size restrictions, the dataset is not included in this repository.  
You can download it from the following link:  

👉 [Download Dataset](https://docs.google.com/spreadsheets/d/1hslhiMjoFTiCvKDTq5eYgd1PA2tzjNEe/edit?usp=drive_link&ouid=117197816922068948990&rtpof=true&sd=true)  

The dataset contains the following important columns:
- Age, Occupation, Annual Income  
- Num_Bank_Accounts, Num_Credit_Card, Interest_Rate  
- Delay_from_due_date, Num_of_Delayed_Payment  
- Credit_Utilization_Ratio, Credit_History_Age, Payment_Behaviour  
- Target: `Credit_Score` (Poor, Standard, Good)

---

##  Model Development
1. **Data Preprocessing**  
   - Handling missing values  
   - Label encoding for categorical variables  
   - Feature scaling  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots  
   - Correlation analysis  
   - Outlier detection  

3. **Machine Learning Models Used**  
   - Logistic Regression  
   - Random Forest  
   - Gradient Boosting (Final Selected Model)  

4. **Final Model: Gradient Boosting Classifier**  
   - Achieved best accuracy among tested models  
   - Saved as `gradient_boosting_model.pkl`  

---

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Credit-Score-Prediction.git
   cd Credit-Score-Prediction
