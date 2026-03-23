# Naveena DS Case Study 2026

## Objective

The goal of this project is to predict kit cycle times for product orders using various datasets, including:

- `train.csv`: Contains 179,853 product orders with kit_start/kit_end dates (target).
- `inference.csv`: Includes 12,069 orders for which kit_end needs to be predicted.
- `calendar.csv`: Provides the fiscal calendar with holidays and weekends.
- `capacity.csv`: Details daily factory capacity (hours and overtime).
- `expected_minutes.csv`: Lists expected build, burn, and kit minutes per product family.

## Steps Followed

1. Exploratory Data Analysis (EDA):

   - Data loading and inspection.
   - Analysis of data types, missing values, and duplicates.
   - Univariate and bivariate analysis.
   - Feature engineering and data leakage checks.
2. Data Cleaning and Preprocessing:

   - Handling missing values and outliers.
   - Encoding categorical variables.
   - Scaling numerical features.
3. Model Training and Evaluation:

   - Predicting `kit_cycle_days` using machine learning models.
   - Evaluating model performance using metrics like RMSE and R².

## Requirements

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

## Folder Structure

- `data/raw`: Place raw input data.
- `data/output`: Includes final outputs and predictions.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/knaveenaa/Naveena_DS_Case_Study_2026.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Naveena_DS_Case_Study_2026
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook for analysis and predictions.
