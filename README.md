# Chronic-Kidney-Disease-Prediction
This project uses patient data to predict whether someone is likely to have chronic kidney disease using a decision tree classifier

This project is a beginner-friendly machine learning classification task that predicts whether a person has chronic kidney disease (CKD) based on medical data. It uses a clean, step-by-step process for data cleaning, exploration, and building a decision tree model.

---

##  Dataset

- The dataset was taken from a CSV file (`kidney_disease.csv`) which contains anonymized patient health data.
- Features include age, blood pressure, sugar level, hemoglobin, diabetes status, etc.
- The target variable is `class`:  
  - `1` = CKD  
  - `0` = Not CKD

---

##  Tools and Libraries

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn

---

## Project Workflow

1. **Data Import & Cleaning**
   - Removed unnecessary columns (like ID)
   - Renamed columns for readability
   - Handled missing values using mean/mode imputation
   - Converted text to numeric for machine learning

2. **Exploratory Data Analysis (EDA)**
   - Checked correlation using heatmaps
   - Visualized class balance (CKD vs. Not CKD)

3. **Model Building**
   - Split data into training and testing sets (75/25)
   - Used Decision Tree Classifier
   - Evaluated with accuracy, confusion matrix, and classification report

---

##  Results

- The model predicts chronic kidney disease based on input features.
- Performance was evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

##  What I Learned

- Data preprocessing is the foundation of any ML project
- How to handle missing data
- How to convert text into numeric labels
- How to build and test a simple classification model

---

##  Future Improvements

- Try different algorithms (Random Forest, Logistic Regression)
- Tune model parameters
- Deploy the model as a web app using Streamlit or Flask

---

##  How to Run This Notebook

1. Download the Jupyter Notebook: `Chronic_Disease_Prediction(1).ipynb`
2. Place the dataset file `kidney_disease.csv` in the same folder
3. Run the notebook step-by-step using Jupyter Notebook or Google Colab

---


