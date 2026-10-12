# PREDICTION OF AGRICULTURE CROP PRODUCTION IN INDIA

**Machine Learning Internship Project Report**

**Submitted by:** E. Mathavi

**Project Domain:** Machine Learning

**Programming Language:** Python

**Platform:** Google Colab

## 1. Abstract

Agriculture plays an important role in India's economy. Crop production depends on various factors, including cultivated area, crop type, location, and year. This project demonstrates the use of Machine Learning to estimate crop production from historical agricultural records. Python libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn are used for data processing, visualization, model development, and evaluation.

## 2. Problem Statement

Understanding agricultural production patterns is important for studying crop trends. This project applies a regression algorithm to historical agricultural data to estimate production based on available input features.

## 3. Objectives

- Analyze agricultural crop production data.
- Clean and preprocess the dataset.
- Develop a Linear Regression model.
- Evaluate the model using MAE, RMSE, and R².
- Visualize actual and predicted production.
- Export prediction results and document the workflow.

## 4. Technologies Used

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Joblib

## 5. Methodology

1. Collect and load an agricultural crop production dataset.
2. Inspect and clean missing or invalid values.
3. Select relevant input features and the production target.
4. Encode categorical features and impute missing input values.
5. Split the data into training and testing sets.
6. Train a Linear Regression model.
7. Evaluate the model using regression metrics.
8. Generate visualizations and export predictions to CSV files.
9. Save the trained model and project outputs.

## 6. Results and Discussion

The model was evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and the R² score. The actual-versus-predicted graph was used to compare model estimates with recorded production values.

**Actual results:** Insert the metric values produced by your Google Colab execution. Do not enter estimated or invented scores.

## 7. Limitations

Model performance depends on the quality and quantity of the available data. A random train-test split may not measure future-year forecasting performance accurately. The model does not establish causal relationships between agricultural factors and production.

## 8. Future Enhancements

- Compare Linear Regression with Random Forest Regression.
- Include additional verified agricultural and weather features.
- Evaluate the model on later years using time-based validation.
- Develop a simple web application for interactive predictions.
- Improve model performance using larger and reliable datasets.

## 9. Conclusion

This project demonstrates an end-to-end Machine Learning workflow for crop production estimation, including data preprocessing, model training, evaluation, visualization, prediction, and documentation. The results should be interpreted according to the dataset's quality and the model's measured performance.

## 10. References

- Python documentation: https://docs.python.org/3/
- Pandas documentation: https://pandas.pydata.org/docs/
- Scikit-learn documentation: https://scikit-learn.org/stable/
- Matplotlib documentation: https://matplotlib.org/stable/
- Dataset source: Add the exact dataset title, URL, publisher, and license used in this project.
