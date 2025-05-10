credit-score-classification/
│
├── data/
│   ├── raw/
│   │   ├── README.md               # Added dataset documentation
│   │   ├── train.csv
│   │   └── test.csv
│   └── processed/
│       ├── cleaned_data.csv
│       └── feature_engineered_data.csv
│
├── notebooks/
│   ├── 0_dataset_download.ipynb     # Added notebook for dataset setup
│   ├── 1_data_exploration.ipynb
│   ├── 2_data_cleaning.ipynb
│   ├── 3_feature_engineering.ipynb
│   ├── 4_model_training.ipynb
│   └── 5_model_evaluation.ipynb
│
├── docs/                           # Added documentation folder
│   ├── dataset_license.md
│   └── kaggle_setup.md
│
├── src/
│   ├── data_processing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── utils.py
│
├── models/
│   ├── random_forest_model.pkl
│   └── xgboost_model.pkl
│
├── reports/
│   ├── EDA_report.pdf
│   ├── feature_importance.png
│   └── model_performance.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── kaggle.json                     # For Kaggle API access
