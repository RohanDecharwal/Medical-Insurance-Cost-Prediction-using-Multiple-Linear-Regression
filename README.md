## Medical Insurance Cost Prediction using Multiple Linear Regression

### Student Details

- **Name:** Rohan Ramdhan Decharwal
- **Course:** AI/ML Internship
- **Batch:** Batch 1(A)
- **Mentor:** Nishant Shrivastava

---

# Objective

The objective of this project is to develop a Multiple Linear Regression model that predicts the medical insurance charges of individuals based on their personal and health-related information. The project demonstrates the complete machine learning workflow, including data preprocessing, feature encoding, model training, evaluation, and interpretation of results.

---

# Dataset

**Medical Cost Personal Insurance Dataset**

**Kaggle Link:**
https://www.kaggle.com/datasets/mirichoi0218/insurance

**Dataset Features**

- Age
- Sex
- BMI
- Children
- Smoker
- Region

**Target Variable**

- Charges

---

# Libraries Used

The following Python libraries were used in this project:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# Methodology

The project was completed using the following steps:

1. Loaded the dataset using Pandas.
2. Explored the dataset and identified numerical and categorical features.
3. Checked for missing values.
4. Encoded categorical variables (`sex`, `smoker`, and `region`).
5. Split the dataset into 80% training data and 20% testing data.
6. Built a Multiple Linear Regression model using Scikit-learn.
7. Predicted insurance charges on the test dataset.
8. Evaluated the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
9. Visualized the model performance using an Actual vs Predicted scatter plot.

---

# Results

The Multiple Linear Regression model was successfully trained to predict medical insurance charges. The model's performance was evaluated using MAE, MSE, and R² Score. The Actual vs Predicted scatter plot showed that the predicted values closely followed the actual insurance charges, indicating that the model learned the relationship between the input features and the target variable reasonably well.

---

# Conclusion

This project demonstrates how Multiple Linear Regression can be used to predict medical insurance charges using customer information such as age, BMI, smoking status, number of children, sex, and region. Among these features, smoking status and BMI have a significant impact on insurance charges. The model provides a simple and interpretable approach for prediction. However, one limitation of Linear Regression is that it assumes a linear relationship between the input features and the target variable, which may not always capture complex real-world patterns. More advanced machine learning models may achieve better predictive performance.

---

# Repository Structure

```
├── Medical Insurance Cost Prediction using Multiple Linear Regression.ipynb
├── README.md
```

---

# Author

**Rohan Ramdhan Decharwal**

**AI/ML Internship - Batch 1(A)**

**Mentor:** Nishant Shrivastava
