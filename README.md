# Heart Disease Analysis

![Heart Disease](https://img.shields.io/badge/Heart%20Disease-Analysis-red)

## 📊 Project Overview

The **Heart Disease Analysis** project aims to explore and analyze data related to heart disease, identifying key factors that contribute to the presence of heart disease in individuals. By leveraging data analytics and machine learning, this project seeks to provide insights that can aid in early detection, prevention, and management of heart conditions.

## 🗂️ Dataset Overview

- **Source**: The dataset is sourced from various heart disease studies, commonly found in repositories like [Kaggle](https://www.kaggle.com/) and UCI Machine Learning Repository.
- **Description**: The dataset contains patient records with various clinical features and the target variable indicating the presence of heart disease.

### Key Features:

1. **Age**: Age of the patient (years).
2. **Sex**: Sex of the patient (`1` = Male, `0` = Female).
3. **ChestPainType**: Type of chest pain experienced by the patient:
   - `TA`: Typical Angina
   - `ATA`: Atypical Angina
   - `NAP`: Non-Anginal Pain
   - `ASY`: Asymptomatic
4. **RestingBP**: Resting blood pressure (mm Hg).
5. **Cholesterol**: Serum cholesterol in mg/dL.
6. **FastingBS**: Fasting blood sugar (`1` = > 120 mg/dL, `0` = < 120 mg/dL).
7. **RestingECG**: Resting electrocardiogram results:
   - `Normal`: Normal ECG
   - `ST`: Having ST-T wave abnormality
   - `LVH`: Showing probable or definite left ventricular hypertrophy
8. **MaxHR**: Maximum heart rate achieved during exercise.
9. **ExerciseAngina**: Exercise-induced angina (`Y` = Yes, `N` = No).
10. **Oldpeak**: ST depression induced by exercise relative to rest.
11. **ST_Slope**: The slope of the peak exercise ST segment:
    - `Up`: Upsloping
    - `Flat`: Flat
    - `Down`: Downsloping
12. **HeartDisease**: Target variable indicating the presence of heart disease (`1` = Heart Disease, `0` = No Heart Disease).

## 🛠️ Tools and Technologies

- **Python**: Primary programming language used for analysis.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-Learn**: For implementing machine learning models.
- **Jupyter Notebook**: For interactive data analysis and model building.

## 📈 Analysis Workflow

1. **Data Cleaning**: Handling missing values, data type conversions, and preparing the data for analysis.
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing distributions of age, cholesterol levels, and blood pressure.
   - Analyzing correlations between features like chest pain type, exercise-induced angina, and heart disease presence.
3. **Feature Engineering**: Transforming and creating new features to enhance model performance.
4. **Predictive Modeling**:
   - Implementing models like Logistic Regression, Decision Trees, and Random Forests.
   - Evaluating models using metrics such as accuracy, precision, recall, and ROC-AUC score.
5. **Data Visualization**: Displaying relationships between key features and heart disease outcomes using plots.

## 📊 Key Insights

- **Age and Heart Disease**: Higher age is generally associated with an increased risk of heart disease.
- **Chest Pain Type**: Typical Angina (TA) is highly associated with heart disease presence.
- **Exercise Angina**: Patients experiencing exercise-induced angina are more likely to have heart disease.
- **Cholesterol and Blood Pressure**: Elevated cholesterol and blood pressure levels are significant indicators of heart disease risk.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook (optional for running the project interactively)

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/heart-disease-analysis.git
cd heart-disease-analysis
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Running the Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook Heart_Disease_Analysis.ipynb
```

Run each cell in the notebook to perform the data analysis and modeling steps.

## 🤝 Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## 📬 Contact

For questions, feedback, or collaboration, reach out at achyuthags755@gmail.com.

---

⭐ If you find this project helpful, please give it a star!
```
