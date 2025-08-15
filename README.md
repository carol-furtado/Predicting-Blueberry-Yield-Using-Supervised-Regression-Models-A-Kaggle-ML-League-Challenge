# WEC-competiton: Predicting Blueberry Yield Using Supervised Regression Models – A Kaggle ML League Challenge

# Predicting Blueberry Yield Using Supervised Regression Models

**Kaggle ML League Challenge** – Regression-based prediction of blueberry crop yield.

---

##  Overview  
This project aims to predict blueberry yield using supervised regression techniques. Developed for the Kaggle ML League, it involves data exploration, feature engineering, model training & evaluation, and result visualization.

---

##  Table of Contents  
- [Dataset](#-dataset)  
- [Approach](#-approach)  
- [Modeling](#-modeling)  
- [Usage](#-usage)  
- [Results](#-results)  
- [Project Structure](#-project-structure)  
- [Tools & Libraries](#-tools--libraries)  
- [How to Reproduce](#-how-to-reproduce)

---

##  Dataset  
- Data contains agronomic and environmental features related to blueberry cultivation.  
- Used features such as plant traits, bee diversity, soil, climate metrics to model yield.  
*(Feel free to add a line or two about train/test data size or source if you summarised it in your notebook.)*

---

##  Approach  
1. **Exploratory Data Analysis (EDA):** Identified feature correlations and missing values.  
2. **Feature Engineering:** Created new features and handled data preprocessing.  
3. **Model Training:** Compared multiple regression algorithms (e.g., Linear Regression, Random Forest, XGBoost).  
4. **Cross-Validation & Hyperparameter Tuning:** Used CV to optimize model performance.  
5. **Evaluation:** Reported metrics like MAE, RMSE for model comparison.

---

##  Modeling  
- Evaluated and compared model performance side by side.  
- Selected the best-performing regression model based on validation scores.  
- **Insert final model choice here**, e.g., LightGBM with tuning parameters.

---

##  Usage  
```bash
# If converting this notebook to script:
python model.ipynb
# Or convert to .py and run:
python train_blueberry_yield.py


