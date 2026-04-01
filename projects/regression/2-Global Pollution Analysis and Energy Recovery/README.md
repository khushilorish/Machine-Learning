♻️ Energy Recovery Prediction using Pollution Data

📌 Overview
This project aims to predict Energy Recovery (in GWh) based on environmental and economic factors such as pollution indices, industrial waste, and energy consumption.
The goal is to analyze whether pollution-related features can effectively explain and predict energy recovery.

📂 Dataset
The dataset contains features such as:
Air Pollution Index
Water Pollution Index
Soil Pollution Index
Industrial Waste (in tons)
CO2 Emissions (in MT)
Energy Consumption Per Capita (in MWh)
Population
GDP Per Capita
Plastic Waste Produced
Energy Recovered (Target Variable)

⚙️ Workflow
1. Data Preprocessing
Removed duplicate values
Handled missing values
Encoded categorical variables (Country)
Removed irrelevant features (Country, Year for modeling)
2. Exploratory Data Analysis (EDA)
Distribution analysis using histograms
Pairplot to examine relationships between features
Correlation heatmap to identify feature relevance
Boxplot to detect outliers
Key Insight:
Most features showed very weak correlation with Energy Recovery.
3. Feature Selection
Used correlation analysis
Applied Random Forest feature importance
Removed low-impact and noisy features
4. Model Building
The following models were implemented:
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
5. Model Evaluation
Metric used: R² Score
Linear models performed poorly due to weak relationships
Tree-based models performed relatively better


📊 Results
Overall model performance was low (negative/low R²)
Indicates weak dependency between features and target
Even advanced models could not significantly improve accuracy

🧠 Key Insights
No strong linear or non-linear patterns found in data
Pollution indicators alone are not sufficient to predict energy recovery
Data likely lacks important predictive features

⚠️ Limitations
Weak feature-target relationships
Possible synthetic or low-quality dataset
Limited feature set

✅ Conclusion
Energy recovery could not be accurately predicted using the given dataset.
The primary limitation lies in data quality and feature relevance, not the modeling techniques.