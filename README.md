# Vehicle-maintenance-prediction
Machine learning project for predictive vehicle maintenance - A4 MMN3 - ESILV 2025
# Predictive Maintenance for Vehicles

This project uses machine learning to predict whether a vehicle needs maintenance based on its operational data.

##  Objective
Build a binary classifier to identify high-risk vehicles and enable proactive maintenance scheduling.

##  Dataset
- Source: [Kaggle - Vehicle Maintenance Data](https://www.kaggle.com/datasets/chavindudulaj/vehicle-maintenance-data)
- 30,000 vehicles, 20 features (mileage, engine size, brake condition, etc.)
- Target: `Need_Maintenance` (0/1)

##  Models Evaluated
- Logistic Regression
- Random Forest
- **Gradient Boosting (final model)**
- KNN, Naive Bayes, Decision Tree
- Ensemble methods (Voting, Bagging, Stacking)

##  Results
- **F1-score**: 1.00  
- **ROC-AUC**: 1.00  
- **Accuracy**: 1.00  
- Best model: Tuned Gradient Boosting with SMOTE and feature engineering.

##  Files
- `notebooks/ML_Project_Final.ipynb`: Full Jupyter Notebook with code and outputs
- `reports/Final_Report_ML.pdf`: Detailed project report (20 pages)

##  How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Open the notebook in Jupyter
3. Run cells sequentially

