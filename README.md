# 🚢 Titanic Survival Prediction using Logistic Regression

This project builds a **logistic regression model** to predict whether a passenger survived the Titanic disaster using a cleaned dataset. The workflow includes data loading, training/testing split, model fitting, evaluation, and visualization with a confusion matrix.

---

## 📁 Dataset

- **File:** `preprocessing_data.csv`
- **Target Variable:** `Survived` (0 = Not Survived, 1 = Survived)
- **Features:** Various cleaned and preprocessed attributes (e.g., `Age`, `Fare`, `Pclass`, `Sex` if encoded, etc.)

---

## 🛠️ Libraries Used

- Python
- Pandas
- Seaborn
- Scikit-learn
- Matplotlib

---

## 📌 Project Workflow

1. **Import Libraries**
   - Pandas, Seaborn, Matplotlib
   - Logistic Regression from `sklearn`

2. **Load Dataset**
   - Read from `preprocessing_data.csv`
   - Preview dataset with `.head()`

3. **Feature & Target Selection**
   - X = "age" and "fare" column
   - y = `Survived` column

4. **Train-Test Split**
   - Split data into training and testing sets (80/20 ratio)

5. **Train Logistic Regression Model**
   - Fit model on training data

6. **Predict & Evaluate**
   - Use `.predict()` to generate predictions
   - Calculate accuracy using `accuracy_score`

7. **Visualize Confusion Matrix**
   - Generate confusion matrix with `seaborn` heatmap


