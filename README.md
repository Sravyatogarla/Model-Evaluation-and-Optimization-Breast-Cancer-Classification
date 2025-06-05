# Model Evaluation and Optimization - Breast Cancer Classification

This project is the **7th Project** in the **Edureka Data Science with SQL Program LMS**, focusing on evaluating and optimizing machine learning models to solve a real-world binary classification problem using the **Breast Cancer Wisconsin dataset**.

---

## 🎯 Project Objective

The goal is to classify tumors as **Malignant (1)** or **Benign (0)** using various classification models and evaluation metrics to determine the best-performing model through tuning and visualization.

---

## 📦 Dataset Information

- Dataset Name: `data.csv` (Breast Cancer Wisconsin Dataset)
- Samples: 569
- Features: 30 numerical features based on tumor characteristics
- Target: Diagnosis (`M` = Malignant, `B` = Benign)

---

## 📂 Repository Structure
├── Model Evaluation and optimization.ipynb  # Main Jupyter Notebook

├── README.md # Project documentation

├──  data.csv # Dataset file 


---

## ✅ Tasks Performed

1. 📥 **Importing and Cleaning Data**  
   - Removed irrelevant columns like `id`, `Unnamed: 32`  
   - Converted target labels (`M`/`B`) to numeric values (1/0)

2. 🔄 **Train-Test Split**  
   - Used `train_test_split` to split data for validation

3. 📊 **Exploratory Data Analysis (EDA)**  
   - Plotted target distribution and feature summary

4. 🌲 **Model Building - Random Forest**  
   - Built a base model and optimized it using **GridSearchCV**

5. ⚙️ **Model Evaluation**  
   - Used metrics: Confusion Matrix, ROC-AUC, Precision-Recall Curve, Classification Report

6. 🤖 **Boosting Models**  
   - Trained **AdaBoost** classifier  
   - Combined **GaussianNB** with AdaBoost for comparison

7. 📈 **Model Comparison**  
   - Compared accuracy scores and visualized model performance

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- GridSearchCV
- AdaBoostClassifier, RandomForestClassifier, GaussianNB

---

## 📌 Topics Covered

- Data preprocessing and cleaning  
- Binary classification  
- Model selection and evaluation  
- Hyperparameter tuning with GridSearchCV  
- Visualization of metrics (ROC-AUC, Precision-Recall)  
- Ensemble methods (Random Forest, AdaBoost, GaussianNB)

---

## 📊 Key Insights & Conclusion

- ✅ The **Random Forest with GridSearchCV tuning** showed the highest performance.
- 🔍 **AdaBoost** and **GaussianNB + AdaBoost** also performed well with lightweight configurations.
- 📈 Evaluation metrics beyond accuracy (like ROC-AUC and Precision-Recall) helped in selecting the most reliable model.
- 📚 This project illustrates real-world **model optimization** strategies that are critical in applied machine learning.

---

## 👩‍💻 Author

**Sravya Togarla**  
GitHub: [Sravyatogarla](https://github.com/Sravyatogarla)  
LinkedIn: [linkedin.com/in/sravya-togarla](https://www.linkedin.com/in/sravya-togarla)

---

## 🎓 Course Credit

This project is completed as part of the **Edureka Data Science with SQL Certification Program**  
🗂️ **Project Number**: 7  
📅 **Module**: Model Evaluation and Optimization

---



