# Analytics
House Predictions


**Housing Price Predictive Analytics**

A complete, leakage-free machine learning pipeline built in Python that predicts housing prices using Linear Regression and Random Forest models, with feature importance analysis.

**Key Features:**
- Proper train/test split performed *before* any preprocessing to avoid data leakage
- Correct scaling technique: `StandardScaler.fit_transform()` on training data only, `.transform()` on test data
- Two models compared: Linear Regression (baseline) vs. Random Forest (ensemble)
- Model evaluation using RMSE, MAE, and R²
- Feature importance visualization
- Clean, modular code structure (separate modules for preprocessing, training, and evaluation)
- Runs out of the box with a bundled 1,200-row synthetic housing dataset — no external downloads needed
- Easily adaptable to any custom CSV dataset

**Tech Stack:** Python, pandas, NumPy, scikit-learn, matplotlib

**Results (on sample data):**
- Linear Regression: R² = 0.944, RMSE = 24,836
- Random Forest: R² = 0.925, RMSE = 28,731

**Project Structure:**
```
predictive-analytics/
├── data/                     # Dataset (CSV)
├── models/                   # Saved models & charts
├── notebooks/                # EDA space
├── src/
│   ├── data_preprocessing.py
│   ├── train_model.py
│   └── evaluate_model.py
├── main.py                   # Runs full pipeline
├── requirements.txt
└── README.md
```

 ML pipeline predicting housing prices with Linear Regression & Random Forest, including feature importance analysis. Built with Python & scikit-learn.


<img width="619" height="500" alt="image" src="https://github.com/user-attachments/assets/df6eb545-406a-41c7-ab24-2080bb79d44d" />
