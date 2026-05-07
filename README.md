
# Metal Parts Defect Prediction & Lifespan Analysis

## Project Overview
This project focuses on predicting the lifespan and defect classification of manufactured metal parts using Machine Learning techniques. The objective was to analyse production parameters, identify factors affecting durability, and build predictive models to support manufacturing quality control and reduce costly destructive testing.

The project includes exploratory data analysis (EDA), preprocessing, feature engineering, regression, and classification modelling using Python and Scikit-learn.

---

## Objectives
- Analyse manufacturing and alloy production data
- Identify key factors influencing metal part lifespan
- Predict lifespan using regression models
- Classify defective and non-defective parts using machine learning
- Compare model performance and evaluate predictive accuracy

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Exploratory Data Analysis (EDA)

### Correlation Analysis
Explored relationships between manufacturing parameters and lifespan using correlation heatmaps.

### Lifespan Distribution
Visualised lifespan distribution to identify skewness, variability, and outliers.

### Categorical Feature Analysis
Used boxplots to analyse how manufacturing categories such as part type and microstructure affect lifespan.

---

## Machine Learning Models

### Regression Models
- Linear Regression
- Random Forest Regression

### Classification Models
- Logistic Regression
- Support Vector Machine (SVM)

---

## Data Preprocessing
- One-Hot Encoding for categorical variables
- Feature scaling using StandardScaler
- Outlier removal using IQR
- Train-test split (80/20)

---

## Model Evaluation

### Regression Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### Classification Metrics
- Accuracy
- Precision
- Recall
- F1-Score

---

## Results

### Regression Model Performance

| Model | MAE | MSE | R² Score |
|-------|------|------|------|
| Random Forest | 64.77 | 6805.50 | 0.9465 |
| Linear Regression | 270.45 | 102800.10 | 0.1687 |

### Classification Model Performance

| Model | Accuracy | F1-Score |
|-------|------|------|
| Logistic Regression | 81% | 0.75 |
| SVM | 85% | 0.85 |

---

## Visualisations

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.jpeg)

### Lifespan Distribution
![Lifespan Distribution](images/distribution_lifespan.jpeg)

### Categorical Feature Boxplot
![Categorical Features](images/categorical_features.jpeg)

---

## Key Insights
- Cooling rate, quench time, and defect counts strongly influenced lifespan
- Manufacturing categories impacted durability significantly
- Random Forest captured non-linear relationships effectively
- SVM achieved the strongest classification performance

---

## Future Improvements
- Experiment with XGBoost and Gradient Boosting
- Address class imbalance using SMOTE
- Apply PCA for dimensionality reduction
- Deploy as a Streamlit web application

---

## Repository Structure

```bash
metal-parts-defect-prediction-ml/
│
├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
