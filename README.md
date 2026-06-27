# 🏠 House Price Predictor

A Machine Learning project that predicts house prices using a **Random Forest Regressor**, achieving **89.5% accuracy** on the Ames Housing dataset.

> Built as part of my AI/ML learning journey — exploring feature importance, regression models, and data preprocessing.

## 📊 Model Results

| Metric | Value |
|---|---|
| Algorithm | Random Forest Regressor (100 trees) |
| Accuracy (R² Score) | 89.5% |
| Mean Absolute Error | $19,164 |
| Dataset Size | 1,460 houses, 7 features |


## 🔍 Key Findings

- **Overall Quality** is the most influential feature — contributing **57.9%** of prediction importance
- **Living area (GrLivArea)** matters more than number of bedrooms
- **Bedrooms** are the least important feature (only **1.3%** importance) — counterintuitive but data-backed


## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.12 | Core language |
| scikit-learn | Model training & evaluation |
| pandas & numpy | Data cleaning & manipulation |
| matplotlib & seaborn | Visualizations |
| Jupyter Notebook | Development environment |


## 📁 Project Structure

```
house-price-predictor/
├── notebooks/
│   └── house_prices.ipynb   ← main notebook (EDA + model)
├── README.md
├── requirements.txt          ← install dependencies
└── .gitignore
```


## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/aakriti-5/house-price-predictor.git
cd house-price-predictor

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook notebooks/house_prices.ipynb
```


## 📈 What I Learned

- How to preprocess real-world housing data (handling missing values, encoding)
- Training and tuning a Random Forest model
- Interpreting feature importance scores
- Evaluating regression models using R² and MAE


## 🔮 Future Improvements

- [ ] Try XGBoost and compare performance
- [ ] Add more features from the full Ames dataset (currently using 7 of 80)
- [ ] Build a simple web UI using Streamlit for live predictions
- [ ] Hyperparameter tuning with GridSearchCV


---




