# 🌫️ PM2.5 Pollution Level Analysis and Forecasting in Kazakhstan Cities (2023)

## 📌 Project Title  
**PM2.5 Pollution Level Analysis and Forecasting in Kazakhstan Cities (2023)**

## 📖 Introduction  
This project analyzes and forecasts PM2.5 air pollution levels in major cities across Kazakhstan for the year 2023. Utilizing real-world air quality data, we performed data cleaning, visualization, and predictive modeling to understand pollution patterns and predict future air quality trends.

## ❗ Problem Statement  
Air pollution poses significant health risks, particularly fine particulate matter (PM2.5), which can penetrate deep into the lungs and bloodstream. In Kazakhstan, tracking and forecasting PM2.5 levels are crucial for developing preventive measures, policy planning, and raising public awareness. This project addresses the lack of accessible, city-specific air quality forecasting in Kazakhstan.

## 🎯 Objectives  
- Clean and preprocess the PM2.5 dataset for Kazakhstan cities  
- Analyze monthly and annual pollution trends across cities  
- Visualize seasonal and geographical pollution patterns  
- Develop and evaluate machine learning models to forecast PM2.5 levels  
- Provide actionable insights through forecasting and comparisons

## 🛠️ Technology Stack  
- **Languages**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels  
- **Tools**: Jupyter Notebook, Kaggle  
- **Others**: Git, GitHub for version control

## 📁 Dataset  
- **Source**: [Asia 2023 Air Report – Kaggle](https://www.kaggle.com/datasets/shruthiiiee/asia-2023-air-report-2000-cities)  
- **Key Features**:  
  - `Rank`, `City`, `Country`, `2023` (annual average)  
  - Monthly PM2.5 levels: `Jan`, `Feb`, `Mar`, `Apr`, `May`, `Jun`, `Jul`, `Aug`, `Sep`, `Oct`, `Nov`, `Dec`

## 🧹 Steps Performed

### 1. Data Cleaning  
- Handled missing values via mean imputation and linear interpolation  
- Removed duplicate records  
- Converted month columns to numeric types  
- Standardized city names

### 2. Exploratory Data Analysis (EDA)  
- Line plots for monthly trends  
- Bar charts for city-wise yearly averages  
- Heatmaps showing seasonal variation across cities


### 3. Prediction and Modeling
- Used monthly PM2.5 values (Jan–Dec) to predict the annual average (2023) for Kazakhstani cities
- Models: Linear Regression, Random Forest, LightGBM, CatBoost, XGBoost
- Evaluation metrics: MAE, RMSE, R², Cross-Validated R²
- Best performance: CatBoost (MAE: 17.88, R²: 0.102)
- Insight: Low model performance due to data inconsistencies or mismatch between monthly and annual values

## ⚙️ Installation Instructions  

```bash
# 1. Clone the repository
git clone https://github.com/bochida/Air-quality-analysis-and-prediction_19P.git

# 2. Navigate into the project directory
cd Air-quality-analysis-and-prediction_19P

# 3. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 4. Install dependencies
pip install -r requirements.txt

# 5. Launch Jupyter Notebook
jupyter notebook
```
