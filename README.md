# Diabetes Progression Prediction using Linear Regression

This project predicts the progression of diabetes in patients using a machine learning model called **Linear Regression**. The model learns from patient medical data, such as age, BMI, blood pressure, cholesterol levels, and other features, to estimate the disease progression.

---

# Dataset

The dataset contains **442 patients** and **10 features**:

- **age** – Age of the patient (standardized)
- **sex** – Gender of the patient (standardized)
- **bmi** – Body Mass Index (standardized)
- **bp** – Average blood pressure (standardized)
- **s1** – Total serum cholesterol (standardized)
- **s2** – Low-density lipoproteins (standardized)
- **s3** – High-density lipoproteins (standardized)
- **s4** – Total cholesterol / HDL (standardized)
- **s5** – Log of serum triglycerides (standardized)
- **s6** – Blood sugar level (standardized)
- **target** – Disease progression measurement after one year (target variable)

The dataset is saved as **`diabetes.csv`**.

---

# Steps Followed

1. **Data Exploration**  
   Checked the first rows, feature types, and basic statistics.

2. **Data Cleaning**  
   Since the dataset is already standardized and complete, no missing values required handling.

3. **Train-Test Split**  
   Split data into **training (75%)** and **testing (25%)** sets.

4. **Model Training**  
   Used **Linear Regression** to train the model on the training data.

5. **Prediction**  
   Predicted disease progression on the test set.

6. **Evaluation**  
   - Converted regression output to classes using the median for confusion matrix  
   - Created **Confusion Matrix** to check classification accuracy

7. **Visualization**  
   - Scatter plot comparing **Actual vs Predicted progression**  
   - Heatmap of **Confusion Matrix**

---

# How to Run

1. Make sure Python and required libraries are installed:  
   ```bash
   pip install numpy pandas matplotlib scikit-learn
