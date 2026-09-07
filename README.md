# diabetes-prediction

# 🩺 Diabetes Risk Prediction

This project focuses on Exploratory Data Analysis (EDA), Dimensionality Reduction, and Classification models to predict the risk of diabetes based on clinical and lifestyle factors.

## 📌 Project Overview

The objective of this analysis is to explore health indicators, preprocess medical data, and build machine learning models to identify individuals at high risk for diabetes.

### 🛠️ Key Steps Included:
1. **Exploratory Data Analysis (EDA):** Statistical summaries, missing values analysis, and distribution checks.
2. **Feature Preprocessing:** Column scaling and categorical/numerical feature grouping.
3. **Dimensionality Reduction & Visualization:** Dimensionality reduction techniques (PCA, t-SNE, Isomap).
4. **Classification:** Machine Learning models (Logistic Regression, Random Forest).


## 📊 Dataset Description

The dataset consists of **18 parameters** related to personal medical history and lifestyle choices:

| Feature | Description | <br>
| **`Age`** | Encoded age category (1 to 13) |<br>
| **`Sex`** | Gender (0: Female, 1: Male) |<br>
| **`HighBP`** | High blood pressure (0: No, 1: Yes) |<br>
| **`HighChol`** | High blood cholesterol (0: No, 1: Yes) |<br>
| **`CholCheck`** | Cholesterol check in past 5 years (0: No, 1: Yes) |<br>
| **`BMI`** | Body Mass Index |<br>
| **`Smoker`** | Smoked >= 100 cigarettes in lifetime (0: No, 1: Yes) |<br>
| **`HeartDiseaseorAttack`** | History of heart attack or heart disease (0: No, 1: Yes) |<br>
| **`PhysActivity`** | Physical activity in the past 30 days (0: No, 1: Yes) |<br>
| **`Fruits`** | Consumes fruit >= 1 time per day (0: No, 1: Yes) |<br>
| **`Veggies`** | Consumes vegetables >= 1 time per day (0: No, 1: Yes) |<br>
| **`HvyAlcoholConsump`** | Heavy alcohol consumption (0: No, 1: Yes) |<br>
| **`GenHlth`** | Self-reported general health rating (1: Excellent - 5: Poor) |<br>
| **`MentHlth`** | Days of poor mental health in past 30 days (0–30) |<br>
| **`PhysHlth`** | Days of poor physical health in past 30 days (0–30) |<br>
| **`DiffWalk`** | Serious difficulty walking or climbing stairs (0: No, 1: Yes) |<br>
| **`Stroke`** | History of stroke (0: No, 1: Yes) |<br>
| **`Diabetes`** | **Target variable** (0: No diabetes/prediabetes, 1: Diabetes/prediabetes) |<br>

*Data Source:* [Kaggle Diabetes Dataset](https://www.kaggle.com/datasets/prosperchuks/health-dataset?select=diabetes_data.csv)


## ⚙️ Tech Stack & Requirements

To run the notebook, install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn

```


## 🚀 How to Run

1. Clone the repository:
```bash
git clone [https://github.com/marianazamorylo/diabetes-prediction.git](https://github.com/marianazamorylo/diabetes-prediction.git)
cd diabetes-prediction

```
2. Download `diabetes_data.csv` and place it in the project root directory.
3. Open and run the Jupyter Notebook:
```bash
jupyter notebook project.ipynb
