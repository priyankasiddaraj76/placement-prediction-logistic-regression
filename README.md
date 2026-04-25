# Placement Prediction using Logistic Regression

## Overview
This project predicts whether a student will be placed or not based on key academic and aptitude features such as **CGPA** and **IQ**. It uses a **Logistic Regression** model for binary classification.

The goal is to understand how simple features can be used to make meaningful predictions in a placement scenario.

---

## Features
- Data visualization using scatter plots
- Binary classification using Logistic Regression
- Decision boundary visualization
- Model evaluation

---

## Machine Learning Workflow

1. **Data Collection**
   - Dataset contains:
     - `cgpa`: Student’s academic performance
     - `iq`: Aptitude score
     - `placement`: Target variable (0 = Not Placed, 1 = Placed)

2. **Data Visualization**
   - Scatter plot to observe distribution:
     ```python
     plt.scatter(df['cgpa'], df['iq'], c=df['placement'])
     ```

3. **Preprocessing**
   - Feature selection (`cgpa`, `iq`)
   - Train-test split

4. **Model Training**
   - Logistic Regression model is trained on the dataset

5. **Decision Boundary**
   - Visualized using `mlxtend.plotting.plot_decision_regions`

6. **Evaluation**
   - Accuracy score used to measure performance

---

## Model Used

### Logistic Regression
- Suitable for binary classification
- Outputs probability of placement
- Uses sigmoid function

---


