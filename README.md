## Project Overview

The Belarus Car Price Prediction project aims to forecast the prices of cars in Belarus by leveraging a dataset containing essential car features. These features include the make, model, year of production, condition, mileage, fuel type, engine volume, color, transmission type, drive unit, and segment. With a total of 56,244 rows and 12 columns, this project seeks to identify the key variables that have the most significant impact on car prices within the Belarusian market.

### Summary and Conclusion for Belarus Car Price Prediction Dataset

In this project, our objective was to predict car prices in Belarus using a given dataset. The steps involved in the data preprocessing and model training are detailed below:

1. Handling Missing Values:
   - Columns with missing values were filled using custom functions to ensure the distribution of the data remained intact. This step was crucial to maintain the integrity of the dataset.

2. Reduction of Unique Values:
   - The car_make column had a large number of unique values, which were reduced to simplify the model and improve performance.

3. Removal of Outliers:
   - Outliers were identified and removed from the dataset to ensure that extreme values did not negatively impact the model’s performance.

4. Data Visualization:
   - Comprehensive data visualizations were performed to gain insights into the data and understand patterns that could be leveraged for prediction. These visualizations helped in identifying relationships between different features and the target variable.

5. Standardization and Label Encoding:
   - Numerical features were standardized to ensure consistent scaling.
   - Categorical features were label-encoded to convert them into a format suitable for the machine learning model.

6. Model Training:
   - An XGBoost (XGB) model was trained on the preprocessed data. XGBoost was chosen for its efficiency and superior performance in handling structured data.

7. Model Performance:
   - The trained XGBoost model achieved an accuracy of 88%. This indicates that the model performs well in predicting car prices based on the given features.

### Conclusion

This project followed a structured approach to handle the Belarus car price prediction dataset. The initial steps focused on filling missing values in a way that preserved the data distribution, reducing the number of unique values in certain columns, and removing outliers. Thorough data visualization provided valuable insights into the dataset. Standardization and label encoding prepared the data for effective modeling. The XGBoost model, known for its robustness and high performance, proved effective in predicting car prices, achieving an accuracy of 88%.

This approach highlights the importance of meticulous data preprocessing, including handling missing values, reducing complexity, and removing outliers. The successful application of the XGBoost model demonstrates its suitability for similar regression tasks in structured datasets.


### *Developed by Hosein Mohammadi*

GitHub : https://github.com/Hosein541

LinkedIn : https://www.linkedin.com/in/hosein-mohammadi-979b8a2b2/

Gmail : Huseinmohammadi83@gmail.com
