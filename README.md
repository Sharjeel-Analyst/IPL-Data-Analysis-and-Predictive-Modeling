#IPL Data Analysis & Predictive Modeling 🏏

This repository contains a Jupyter Notebook (Final_Code_Aug28.ipynb) that explores IPL (Indian Premier League) ball-by-ball match data and applies machine learning models to extract insights and make predictions.

Project Overview

Perform exploratory data analysis (EDA) on IPL datasets.

Visualize key insights using Seaborn and Matplotlib.

Apply feature engineering and data preprocessing.

Train and evaluate predictive models including:

Random Forest Classifier

XGBoost Classifier

Measure performance with accuracy, precision, recall, F1-score, and confusion matrices.

"Dataset"

The project uses IPL datasets, primarily:

deliveries.csv → Ball-by-ball information of IPL matches.

(Optional) Other IPL-related datasets if available.

You can download the dataset(s) from Kaggle – IPL Dataset
 or provide your own CSV files in the same directory.

Installation & Requirements

Clone the repository and install dependencies:

pip install -r requirements.txt

Required Libraries

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost

scipy

 Usage

Open the Jupyter Notebook:

jupyter notebook Final_Code_Aug28.ipynb


Ensure deliveries.csv and matches.csv is placed in the working directory.

Run the cells step by step to:

Explore IPL data.

Visualize match & player statistics.

Train and evaluate ML models.

 Results

Feature importance from Random Forest and XGBoost.

Performance comparison across models.

Insights into IPL matches from EDA.

 Future Work

Extend dataset to include team-level stats.

Deploy a prediction web app using Streamlit or Flask.

Hyperparameter optimization with GridSearchCV/RandomizedSearchCV.

📜 License

This project is licensed under the MIT License.
