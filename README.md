# Project-4
Project Title: Feature Extraction and Price Prediction for Mobile Phones

# 1. Introduction
This project aimed to develop a predictive model prominent organization that specializes in selling mobile phones. The organization is keen to enhance its pricing strategy by gaining a deeper understanding of the key features that influence the prices of mobile phones in today's highly competitive market. 

# 2. Data Overview
- Dataset: Processed_Flipdata.csv
- Features: Included specifications such as memory, RAM, battery life, camera pixels, and categorical features like model, color, and processor type.
- Target Variable: Prize.

# 3. Data Preprocessing
- Missing Values: Rows with missing values were removed to ensure data integrity.
- Feature Engineering: 
  - Extracted camera specifications into numerical values.
  - Converted categorical features using one-hot encoding.
- Outlier Removal: Employed the IQR method to eliminate outliers in continuous variables, enhancing model robustness.

# 4. Exploratory Data Analysis (EDA)
- Data Visualization: Initial exploratory analyses showed the distribution of prices and the relationships between features.
- Correlation Analysis: Identified strong correlations between specific features (e.g., RAM and price).

# 5. Model Development
- Train-Test Split: The dataset was divided into training (80%) and testing (20%) subsets.
- Standardization: Features were standardized to improve model performance.
- Model Selection: Random Forest Regressor was chosen for its ability to manage non-linear relationships and interactions between features.

# 6. Model Evaluation
- Performance Metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score: 
- Interpretation: The metrics indicated a strong predictive capability of the model, with an R² score close to 1 signifying good fit.

# 7. Results Visualization
- Actual vs. Predicted Prices: A scatter plot was created, showcasing the model's predictions against actual prices, demonstrating a close alignment.

# 8. Conclusion
The Random Forest model effectively predicts mobile phone prices based on various features. While the results are promising, potential improvements include hyperparameter tuning and exploring other regression techniques.
