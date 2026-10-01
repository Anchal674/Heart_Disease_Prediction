# Heart_Disease_Prediction

This project is a **Machine Learning-based classification system** that predicts the likelihood of heart disease based on various patient health and clinical parameters.

The project covers the complete Machine Learning workflow, including **data preprocessing, exploratory data analysis, feature encoding, model training, prediction, and model evaluation**.

---

## 📦 Project Features

-  **Data Preprocessing**: Cleaning and preparing healthcare data for Machine Learning
-  **Exploratory Data Analysis**: Analyze patient health patterns and relationships between features
-  **Feature Encoding**: Convert categorical variables into numerical values
-  **ML Classification**: Train a Machine Learning classification model
-  **Heart Disease Prediction**: Predict whether a patient is likely to have heart disease
-  **Model Evaluation**: Evaluate model performance using classification metrics
-  **Confusion Matrix**: Analyze correct and incorrect predictions
-  **Python Based**: Developed using Python and popular Machine Learning libraries

---

##  Model Input Variables

The prediction model uses different health and clinical parameters as input.

| Feature | Description | Example |
|---|---|---|
| `Age` | Age of the patient | `50` |
| `Sex` | Gender of the patient | `M` |
| `ChestPainType` | Type of chest pain | `ATA` |
| `RestingBP` | Resting blood pressure | `120` |
| `Cholesterol` | Cholesterol level | `200` |
| `FastingBS` | Fasting blood sugar indicator | `0` |
| `RestingECG` | Resting electrocardiogram result | `Normal` |
| `MaxHR` | Maximum heart rate achieved | `150` |
| `ExerciseAngina` | Exercise-induced angina | `N` |
| `Oldpeak` | ST depression value | `1.0` |
| `ST_Slope` | Slope of peak exercise ST segment | `Up` |

###  Target Variable

The model predicts:

| Value | Meaning |
|---|---|
| `0` | No Heart Disease |
| `1` | Heart Disease |

---

##  Machine Learning Workflow

The project follows a complete Machine Learning pipeline:

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Encoding
   ↓
Feature & Target Separation
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
