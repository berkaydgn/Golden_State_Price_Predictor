# California Housing Prices Prediction

A complete end-to-end machine learning pipeline to predict median house values in California districts, featuring data exploration, preprocessing, feature engineering, model training, tuning, and evaluation.

---

## 📖 Project Overview

In this project, we use the California Housing Prices dataset (derived from the 1990 California census) to build and compare regression models that estimate the median house value in each district. The notebook guides you through:

1. **Exploratory Data Analysis (EDA)** – Summary statistics, histograms, and heatmaps to understand distributions and correlations.  
2. **Data Preprocessing** – Cleaning missing values, log-transforming skewed features, scaling, and encoding categorical variables.  
3. **Feature Engineering** – Creating ratio features like bedrooms-per-room and rooms-per-household to capture housing composition.  
4. **Modeling** – Training a baseline Linear Regression model and a Random Forest Regressor.  
5. **Hyperparameter Tuning** – Using GridSearchCV to optimize Random Forest parameters.  
6. **Evaluation** – Comparing models with R², RMSE, and MAE on a held-out test set.  
7. **Insights & Next Steps** – Interpreting feature importances and suggesting improvements.

---

## 🗂️ Dataset

- **Source:** [California Housing Prices (Kaggle)](https://www.kaggle.com/datasets/camnugent/california-housing-prices)  
- **Features:** 10 original attributes (population, median_income, etc.) + engineered features (log transforms, ratio features)  
- **Target:** `median_house_value` (USD)

---

## 🚀 How to Use

1. **Clone this repo**  
   ```bash
   git clone https://github.com/your-username/california-housing-prices.git
   cd california-housing-prices
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the notebook**  
   ```bash
   jupyter notebook California_Housing_Prediction.ipynb
   ```

4. **Follow the workflow** steps in the notebook:  
   - Data loading & cleaning  
   - Visualization & EDA  
   - Preprocessing & feature engineering  
   - Model training & evaluation  
   - Hyperparameter tuning  

---

## 📑 Notebook & Links

- **Kaggle Notebook:** [berkaydogan1/california-housing-prices](https://www.kaggle.com/code/berkaydogan1/california-housing-prices)  
- **LinkedIn:** [linkedin.com/in/berkaydogan-](https://www.linkedin.com/in/berkaydogan-/)  

---

## 👤 Author

**Berkay Doğan**  
Management Information Systems Student & Aspiring Data Scientist  
[LinkedIn Profile](https://www.linkedin.com/in/berkaydogan-/)  

---

## 📈 Results Snapshot

| Model                 | Test R² Score |
|-----------------------|---------------|
| Linear Regression     | 0.66          |
| Random Forest         | 0.81          |
| Optimized RandomForest| 0.82          |

*(Your actual scores may vary based on runs and parameter settings.)*

---

## 🔮 Next Steps

- Hyperparameter tuning with randomized search or Bayesian optimization  
- Ensemble methods (e.g., stacking)  
- Incorporate additional data (e.g., crime rates, school quality)  
- Dashboard or web app to serve predictions in real time  

---

> Feel free to ⭐ the repo if you find it useful and share your feedback!
