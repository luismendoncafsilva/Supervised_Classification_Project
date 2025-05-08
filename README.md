# Supervised_Classification_Project
Churn - Case Study


#  Customer Churn Prediction Project

This project is about predicting **customer churn** — figuring out which customers are likely to leave a company — using machine learning.

The goal is to build a model that helps businesses take action before they lose customers.

---

##  Project Structure

This notebook follows a step-by-step process:

1. **Data Cleaning & Preparation**
   - Removed white spaces, fixed data types, and handled missing values (especially in the `tenure` column).
   - Converted categorical variables into numbers.

2. **Exploratory Data Analysis (EDA)**
   - Visualized data to understand trends and class imbalance.
   - Found that more customers stay (label `0`) than leave (label `1`).

3. **Handling Class Imbalance**
   - Used techniques like resampling and class weights to help the model focus on the minority class (churned customers).


4. **Model Training & Cross-Validation**
   - Tested multiple classification models using cross-validation.
   - Compared performance using metrics like accuracy, precision, recall, and F1-score.

---

##  Machine Learning Models Tested

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors

---

##  Results

- The project helps compare models fairly using cross-validation.
- Class imbalance was handled properly, avoiding misleading accuracy scores.
- The best-performing model can now be used to make predictions and help with business decisions.


---

##  How to Use

You can run the notebook step-by-step in Jupyter Notebook or Google Colab.  
Make sure you have the following libraries installed:

```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
