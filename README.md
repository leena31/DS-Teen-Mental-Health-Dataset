# Teen Mental Health Prediction Using Machine Learning
This project applies machine learning techniques to predict daily stress levels among adolescents using behavioral, contextual, and emotional self-reported data. The study emphasizes balanced evaluation, model interpretability, and stress detection.
Dataset is available on Kaggle: https://www.kaggle.com/datasets/dakshbhatnagar08/inside-teen-minds-global-mental-health-and-habits

# Problem Statement

Teens stress is influenced by multiple interacting factors such as mood, sleep, screen time, social interaction, and academic context.
The goal of this project is to:
Predict daily stress levels (Low, Medium, High) at the student-day level using supervised machine learning models. Applied Logistic Regression, Random Forest, SVM, XGBoost Classification models and evaluatd basis on macro F1-score over accuracy to ensure fair treatment of all stress categories. Also, an ablation study was performed to assess the impact of key features on model performance.


## Project Structure

```text
TEEN_MENTAL_HEALTH/
│
├── data/
│   ├── raw/                  # Original, untouched dataset
│   ├── processed_v1/         # Initial processed dataset (early experiment)
│   └── processed_v2/         # Final processed dataset used for results
│
├── notebooks/
│   ├── 01_eda_notebook.ipynb          # Exploratory Data Analysis
│   ├── 02_data_preparation.ipynb      # Cleaning, encoding, feature engineering
│   ├── 03_modeling_v1.ipynb            # Initial modeling experiments
│   └── 03_modeling_final_v2.ipynb      # Final model training and evaluation
│
├── reports/                  # Final figures, and analysis outputs
│
├── env/                      # Virtual environment
│
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation

# Get Started
python -m venv venv # Create Virtual env
venv\Scripts\activate

pip install -r requirements.txt # Install requirements
