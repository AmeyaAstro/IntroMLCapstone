# IntroMLCapstone - House Price Prediction

## Project Description
Implementation of 5 machine learning models for predicting house prices using the Ames Housing dataset. Includes 3 classical models from course modules and 2 models from recent research papers.

## Files

### Notebooks (Run in this order):
1. **01_Data_Preprocessing_and_EDA.ipynb** - Data cleaning, feature engineering, EDA
2. **02_Classical_ML_Models.ipynb** - 3 classical ML models:
   - Linear Regression (Module 3)
   - Ridge Regression (Module 4 - Regularization)
   - Neural Network (Module 8)
3. **03_Research_Paper_Implementations.ipynb** - 2 research paper models:
   - XGBoost from Sharma et al. (2024)
   - SVR with statistical preprocessing from Vasquez & Chellamuthu (2021)

### Data Files:
- `train.csv` - Original dataset (for Notebook 1)
- `data_description.txt` - Feature descriptions

### Generated Files:
- `processed_data_improved.pkl` - Preprocessed data (created by Notebook 1, used by Notebooks 2 & 3)
- `feature_names.pkl` - Feature names (created by Notebook 1, used by Notebooks 2 & 3)
- `improved_class_models.pkl` - Trained classical models (created by Notebook 2, used by Notebook 3)
- `improved_scaler.pkl` - Feature scaler (created by Notebook 2, used by Notebook 3)

## How to Run

### 1. Clone Repository
```bash
git clone https://github.com/YOUR-USERNAME/IntroMLCapstone.git
cd IntroMLCapstone
