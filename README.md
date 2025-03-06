### Land-Cover-Project
#### Classification Model Development

#### Overview
This project focuses on classifying land cover into three categories: Buildings, Cropland, and Woody Vegetation Cover (>60%). The goal is to support environmental conservation efforts by providing a reliable model that can help monitor and manage land-use changes effectively. The dataset comprises geospatial data reflecting regions undergoing rapid transformation. By leveraging CatBoost, a gradient boosting algorithm optimized for categorical features, we developed a predictive model that outputs occurrence probabilities for each class. The model aids decision-making in sustainable land management by offering high-accuracy classifications and insights into land cover distributions.

#### Features
- Data Loading and Cleaning
- Handling Missing Values and Data Imputation
- Exploratory Data Analysis (EDA) and Visualization
- Feature Engineering and Selection
- Model Training, Tuning, and Evaluation
- Test Results Submission

#### Installation
Ensure you have the required dependencies installed by running:
```bash
pip install pandas geopandas numpy matplotlib seaborn labelencoder optuna catboost 
```

#### Deliverables

- Source Code and Notebooks: The repository contains Jupyter notebooks with data preprocessing, model training using CatBoost, evaluation, and prediction generation.
- Technical Report: A detailed report explaining the methodology, key findings, and model performance insights.
- Test Set Predictions: The final predictions were generated using CatBoost model, and the accuracy, auc metrics, formatted according to the sample submission, and saved as a CSV file.

