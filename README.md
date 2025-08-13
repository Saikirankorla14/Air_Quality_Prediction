# Air_Quality_Prediction

Project Overview
This project aims to forecast pollution levels using historical sensor data. By leveraging time-series forecasting models and spatial analysis, the project provides insights into air quality trends and supports early warnings for high pollution events.
Dataset
The UCI Air Quality dataset contains hourly averaged responses from an array of chemical sensors embedded in an Air Quality Chemical Multisensor Device. It includes measurements of various air pollutants and weather conditions.
Methodology
- Data Cleaning: Handle missing values and erroneous readings.
- Feature Engineering: Extract datetime features and pollutant-specific metrics.
- Time-Series Forecasting: Use FB Prophet to model and forecast pollutant levels.
- Spatial Analysis: Utilize GeoPandas to visualize pollution data geographically (if location data is available).
- Evaluation: Evaluate model accuracy using metrics like MAE and RMSE.
Technologies Used
- Python
- Pandas and NumPy
- FB Prophet
- GeoPandas
- Matplotlib and Seaborn
Learning Outcomes
- Learn how to preprocess environmental sensor data.
- Understand and apply time-series forecasting with FB Prophet.
- Visualize spatial air quality data using GeoPandas.
- Evaluate forecast accuracy using common regression metrics.
How to Run the Project
1. Clone the repository or download the project files.
2. Install required libraries using `pip install -r requirements.txt`.
3. Load the UCI Air Quality dataset.
4. Run the Jupyter Notebook or Python script to preprocess, analyze, and forecast air quality data recognized.

Actual vs. Predicted CO(GT) Pollution Levels:
<img width="996" height="547" alt="Actual vs  Predicted CO(GT) Pollution Levels" src="https://github.com/user-attachments/assets/37af1dca-68eb-461f-a3d6-8acd72d61c8c" />
