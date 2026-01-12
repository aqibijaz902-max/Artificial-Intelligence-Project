# Diabetes Progression Prediction using Linear Regression

---

## 🌟 Project Overview
This project predicts the progression of diabetes in patients using **Linear Regression**, a powerful machine learning algorithm. By analyzing patient medical data such as age, BMI, blood pressure, glucose levels, and other key features, the model estimates the disease progression to help in early intervention and monitoring.

---

## 📊 Dataset Description
- **Dataset Name:** Diabetes Dataset  
- **Source:** [Diabetes Dataset (GitHub)](https://gist.github.com/boersmamarcel/4202286/raw/diabetes.csv)  
- **Number of Rows / Columns:** 768 rows, 9 features + 1 target  
- **Features:**
  - Pregnancies  
  - Glucose  
  - Blood Pressure  
  - Skin Thickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
- **Target Variable:** Outcome (0 = non-diabetic, 1 = diabetic)  
- **Observation:** Patient data is numeric and ready for regression analysis.

---

## 🧹 Data Preprocessing
- Checked for missing values and handled them.  
- Standardized numeric features.  
- Split dataset into **training (75%)** and **testing (25%)** sets.  
- Features selected for the model: all except Outcome.

---

## 🎯 Features and Target Definition
- **Features (X):** Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age  
- **Target (y):** Outcome  

---

## 🛠 Model Training
- **Algorithm Used:** Linear Regression  
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  
- Trained model on training data and predicted diabetes progression on testing data.

---

## 📏 Evaluation Metrics
- **Accuracy**  
- **Precision**  
- **Recall (Sensitivity)**  
- **Specificity**  
- **F1-Score**  
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **R² Score (Coefficient of Determination)**  
- **Support**  

---

## 📈 Actual vs Predicted
A scatter plot is generated to visually compare **actual vs predicted progression**.  

---

## 🔢 Pseudo Confusion Matrix
Shows classification performance in a simplified table.  

---

## 📂 GitHub Repository
- Dataset file: `diabetes.csv`  
- Google Colab Notebook: `Diabetes_Linear_Regression.ipynb`  
- Instructions and code are included in the notebook for easy execution.

---

## 🏃 Instructions to Run
1. Open the Colab notebook `.ipynb` file in **Google Colab**.  
2. Upload the dataset file `diabetes.csv` to Colab.  
3. Run all cells in order to:  
   - Explore dataset info  
   - Preprocess data  
   - Train Linear Regression model  
   - View predictions and evaluation metrics  
   - Generate scatter plot and confusion matrix  

---

## 🎯 Conclusion
This project demonstrates how **Linear Regression** can be applied to predict diabetes progression using medical features. Evaluation metrics, scatter plots, and confusion matrices help validate the model's predictions, making it a useful tool for early detection and monitoring.

---

## 👨‍💻 Author
**Name:** Aqib Ijaz  
**Email:** aqibijaz902@gmail.com
