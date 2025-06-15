# Task 7 - Support Vector Machines (SVM)

## 🔍 Objective
Apply SVM (Support Vector Machine) techniques to a binary classification problem using both **Linear** and **RBF kernels**, including visualization and hyperparameter tuning.

## 📁 Dataset
**Breast Cancer Dataset**  
[Kaggle Source](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)

## ⚙️ Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib / Seaborn

## 📌 Steps Performed
1. **Data Loading & Preprocessing**
   - Loaded CSV data
   - Handled missing values
   - Converted categorical labels to numerical
   - Standardized the features

2. **Model Training**
   - Trained SVM with **Linear kernel**
   - Trained SVM with **RBF (Gaussian) kernel**

3. **Hyperparameter Tuning**
   - Used GridSearchCV to tune `C` and `gamma`

4. **Cross-Validation**
   - Performed 5-fold cross-validation for model evaluation

5. **Visualization**
   - Used PCA for 2D plotting of decision boundaries

## 💡 What I Learned
- How SVM works for classification
- The concept of margin maximization
- Difference between linear and non-linear kernels
- How to prevent overfitting with hyperparameter tuning
