

### **Used Cars Price Prediction**

**Objective**: 
- The goal is to explore, analyze, and visualize a dataset of used cars and build a model to predict their prices.
- The dataset contains comprehensive information on used cars from the Indian market, and the aim is to generate insights and provide recommendations based on the analysis.


### **Data Preparation and Feature Engineering**:
- **Preprocessing**: 
  - Missing values were handled, and outliers in features like kilometers driven were addressed.
  - Features like car name and model were split into brand and model.
  - Skewed features such as mileage and price were log-transformed to improve model interpretation.
- **Feature Correlation**:
  - Key predictors of price include engine power, mileage, kilometers driven, and new price.
  - A negative correlation was found between mileage and engine displacement/power.

### **Model Building**:
- A **linear regression** model was built to predict used car prices based on the provided features.
- **Evaluation Metrics**:
  - R-squared value of about 90%, indicating a good fit.
  - Mean Squared Error (MSE) of 0.03, Mean Absolute Error (MAE) of 0.123, and Root Mean Squared Error (RMSE) of 0.173.

### **Insights**:
- Significant predictors of the used car price include:
  - Year of manufacture
  - Number of seats
  - Engine power
  - Mileage
  - Kilometers driven
  - Location, fuel type, and transmission
- A 1-unit increase in the manufacturing year leads to an estimated increase in price by **1.127 Lakhs**.
- An increase in the number of seats raises the price by **1.028 Lakhs**.

### **Conclusion & Recommendations**:
- The model achieves an accuracy of around 90%, but improvements can still be made by incorporating additional factors like socio-economic data and using more robust techniques.
- A consistent and comprehensive dataset remains crucial for accurate predictions.

