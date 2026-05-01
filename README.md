# MACHINE-LEARNING-PROJECT

# Loan Approval Prediction Using Machine Learning

This project focuses on predicting whether a loan application will be **approved or rejected** using machine learning algorithms. It uses applicant financial and personal information to build predictive models that assist in decision-making.

##  Objective

* Predict loan approval status accurately
* Identify key factors affecting loan approval
* Compare multiple machine learning models
* Improve decision-making in banking systems

##  Dataset Information

* **Dataset:** Loan Prediction Dataset
* **Total Records:** 614
* **Total Features:** 13
* **Target Variable:** `Loan_Status`

---

##  Data Preprocessing

Handled missing values

* Numerical → Median
* Categorical → Mode

 Data Cleaning

* Converted `3+` in Dependents → 3
* Removed inconsistencies

 Encoding

* Label Encoding for categorical variables

##  Feature Engineering

Created new feature:
TotalIncome = ApplicantIncome + CoapplicantIncome

 Applied Log Transformation:
* ApplicantIncome
* LoanAmount
* TotalIncome

 Purpose: Reduce skewness and improve model performance

##  Machine Learning Models:

### 1. Logistic Regression

* Baseline model
* Requires feature scaling
* Works well for linear relationships

###  2. Decision Tree Classifier

* Rule-based model
* Captures non-linear patterns
* Can overfit if not controlled


###  3. Random Forest Classifier

* Ensemble model (multiple decision trees)
* Reduces overfitting
* Most stable and reliable model

## Model Evaluation:

### Metrics Used:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-score

##  Results Comparison:

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 78.86%   |
| Decision Tree       | 77.24%   |
| Random Forest       | 78.05%   |

## Final Conclusion

 Random Forest performed best overall
 Provides balanced and stable predictions
 Reduces overfitting using ensemble learning

##  Key Insights

* Credit History is the most important factor
* Higher income increases approval chances
* Semiurban applicants have higher approval rates

##  Technologies Used:

* Python 
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## TEAM MEMBERS:

**RAMEEN KHAN** (54)
**BISMA NISAR**(3)
**AMNA AZEEM**(6)

**LINKS**:


