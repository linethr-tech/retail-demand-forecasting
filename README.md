# retail-demand-forecasting
Business case: forecasting demand to improve supply chain efficiency
## 📊 Project Overview
This project aims to predict retail sales using historical data, store characteristics, and external economic factors.  
The goal is to support better inventory planning and decision-making.
## Project Progress
### ✅ Data Cleaning
- Loaded and validated multiple datasets
- Ensured consistent data types (e.g., datetime for merging)

### ✅ Exploratory Data Analysis (EDA)
- Identified seasonality patterns in sales
- Detected higher sales during holiday periods
- Found that a small number of stores drive a large portion of revenue

### ✅ Feature Engineering
- Created time-based features (Year, Month, Week)
- Added store-level features (Type, Size)
- Integrated external data (Temperature, Fuel Price, CPI, Unemployment, Markdowns)

### ✅ Data Preprocessing
- Handled missing values (e.g., MarkDowns filled with 0)
- Prepared dataset for modeling

### 🔄🤖 Modelling (Results): train/test split, regression models, evaluation metrics
- Linear Regression:
  - MAE: ~14,561
  - RMSE: ~21,752

- Random Forest:
  - MAE: ~1,523
  - RMSE: ~3,878

Random Forest significantly improved performance, capturing complex patterns in the data. In other words, I built a predictive sales model and significantly improved its accuracy using Random Forest, reducing the error by more than 80%.
