# Macroeconomic Data Project using macro_data_25yrs.csv Dataset
<a href="MacroeconomicDataProject.ipynb" download>View Jupyter Project File</a>

### Program Overview
This project analyzes macroeconomic data spanning the past 7 years to explore relationships between key financial indicators and to develop forecasting models. The dataset includes features such as __M2 money supply__, __10-year Treasury yield__, __Federal Funds Rate__, __Consumer Price Index (CPI)__, __inflation rate__, and __SOFR__. The workflow involves data loading, preprocessing, feature engineering (e.g., yield spread, moving averages, volatility measures), correlation analysis, and time-series modeling.


__Tool 1__: Data Loading and Preprocessing
- Necessary libraries such as pandas, seaborn, and matplotlib are imported, and the Macroeconomic Data dataset (macro_data_25yrs.csv) is uploaded into df and copied as df1 for purposes of analysis. The first ten rows are displayed to inspect the variables. Null (NaN) values are replaced with the mean of the column values. In this case, SOFR was the only column with null values, so its 81 values were filled in with the column mean.

__Tool 2__: Feature Engineering and Correlation Analysis


__Tool 3__: Time Series Modeling
