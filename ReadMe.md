# Titanic Survival Prediction 

This project analyzes the Titanic dataset using various classification algorithms to predict passenger survival.

##  Models Used
- Logistic Regression
- Random Forest
- XGBoost
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## Features Engineered
- Sex encoded as `Sex2`
- Embarked port encoded as `Embarked2`
- Dropped high-null or non-informative columns like `Name`, `Cabin`, `Ticket`
- Imputed missing values for `Age`, `Embarked`, and `Fare`

## Visualizations
- **Correlation heatmap** of features with survival
- **Bar plots** showing survival rates by sex and class
- **Box plots** for age distribution across survival status
- **Feature importance bar plots** for:
  - Logistic Regression (via coefficients)
  - Random Forest and XGBoost (via built-in importance)
- **Pair plots** and **violin plots** to explore feature distributions

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- Feature Importance plots

##  Dataset Source
- [Kaggle: Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset/data)

##  How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/titanic-survival-prediction.git
    cd titanic-survival-prediction
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook titanic_analysis.ipynb
    ```

## 📄 License
This project is licensed under the MIT License.