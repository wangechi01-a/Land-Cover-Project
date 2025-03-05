### Land-Cover-Project
#### Classification Model Development

#### Overview
This project focuses on building a land cover classification model using a dataset containing geographic and environmental features. The goal is to preprocess the data, engineer relevant features, and train a robust classification model to accurately classify different land cover types(building, cropland, watercover).

#### Features
- Data Loading and Cleaning
- Handling Missing Values and Data Imputation
- Exploratory Data Analysis (EDA) and Visualization
- Feature Engineering and Selection
- Model Training, Tuning, and Evaluation

#### Installation
Ensure you have the required dependencies installed by running:
```bash
pip install pandas geopandas numpy matplotlib seaborn labelencoder optuna catboost 
```

#### Usage
1. Load and preprocess the dataset by handling missing values and encoding categorical variables.

2. Perform exploratory data analysis (EDA) to uncover patterns and trends.

3. Engineer and select features to enhance model performance.

4. Train various classification models and compare their performance.

5. Train the final model using CatBoost for optimal performance.

6. Evaluate the models using key performance metrics such as Accuracy, F1-score and  ROC AUC. 

#### Results

The final model, implemented using CatBoost, demonstrated strong classification performance, effectively distinguishing between land cover types. The model efficiently handled categorical features and reduced overfitting, making it highly suitable for environmental and geographic analysis.

