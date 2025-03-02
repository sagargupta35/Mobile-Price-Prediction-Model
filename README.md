# Mobile Price Prediction Model

This repository contains a machine learning model for predicting mobile phone prices based on various features such as storage, RAM, camera specifications, battery capacity, and screen size.

## 📂 Project Structure
- `notebook.ipynb` → Jupyter Notebook containing the entire workflow of data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation.
- `data/` → (If applicable) Folder for dataset files.
- `models/` → (If applicable) Trained models for predictions.

## 📊 Dataset
- The dataset consists of mobile phone specifications and their corresponding launch prices.
- Features include:
  - **Storage, RAM** (in GB)
  - **Front & Back Camera** (in MP)
  - **Battery Capacity** (in mAh)
  - **Screen Size** (in inches)
  - **Launch Price in India (Target Variable)**

## 🛠️ Steps Followed
1. **Data Preprocessing**
   - Handled missing values & outliers.
   - Log transformation for skewed features.
   - Feature scaling & encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions, correlations, and feature relationships.
3. **Feature Engineering**
   - Applied transformations & feature selection.
4. **Model Training & Hyperparameter Tuning**
   - Used `RandomForestRegressor`, `GradientBoostingRegressor` and `GridSearchCV`/`RandomizedSearchCV`/`VotingRegressor`.
5. **Evaluation**
   - Achieved an RMSE of **~14,664** on the test data.

## 🔮 Future Improvements
- Improve model performance using advanced ensemble methods.
- Deploy as a web app for real-time predictions.
- Incorporate additional features like brand, processor type, and build quality.

  ## Authour: `Sagar Gupta`
