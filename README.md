# Titanic Survival Prediction 🚢

This project uses the Titanic dataset to predict whether a passenger survived or not based on demographic and travel information.

The primary goal of this project was not only to build a predictive model but also to understand the mathematics behind Logistic Regression by implementing it from scratch using NumPy and comparing it with Scikit-Learn's implementation.

---

## Project Objectives

* Perform data cleaning and preprocessing
* Handle missing values
* Encode categorical variables
* Split data into training and testing sets
* Standardize features
* Implement Logistic Regression from scratch
* Compare results with Scikit-Learn
* Evaluate model performance

---

## Dataset

Dataset: Titanic - Machine Learning from Disaster

Features used:

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

Target Variable:

* Survived

  * 1 = Survived
  * 0 = Did Not Survive

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Workflow

### 1. Data Preprocessing

* Loaded dataset using Pandas
* Filled missing Age values using median
* Filled missing Fare values using median
* Encoded categorical variables using one-hot encoding
* Selected relevant features

### 2. Train-Test Split

Dataset was divided into:

* 80% Training Data
* 20% Testing Data

### 3. Feature Scaling

StandardScaler was used to standardize numerical features before training.

### 4. Logistic Regression From Scratch

Implemented:

* Sigmoid Function
* Gradient Descent
* Weight Updates
* Bias Updates
* Prediction Function

without using any machine learning libraries.

### 5. Scikit-Learn Comparison

Trained a Logistic Regression model using Scikit-Learn and compared its performance with the custom implementation.

---

## Results

| Model                              | Accuracy |
| ---------------------------------- | -------- |
| Logistic Regression (Scratch)      | XX.XX%   |
| Logistic Regression (Scikit-Learn) | XX.XX%   |

*Replace the values above with your actual results.*

---

## Key Learnings

This project helped me understand:

* How Logistic Regression works internally
* The role of Gradient Descent in optimization
* Data preprocessing techniques
* Feature scaling
* Model evaluation
* The importance of validating datasets and checking for data leakage

One of the most valuable lessons was investigating a suspicious 100% accuracy result, which turned out to be caused by an incorrect dataset rather than a perfect model.

---

## Future Improvements

* Add Confusion Matrix visualization
* Implement Precision, Recall, and F1 Score
* Compare with Random Forest and Decision Tree models
* Perform hyperparameter tuning
* Deploy the model using Streamlit

---

## Author

Raghav Ratan Yadav

Final Year Integrated M.Sc. Mathematics
NIT Rourkela

Aspiring Data Analyst | Machine Learning Enthusiast
