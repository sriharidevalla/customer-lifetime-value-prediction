# Customer Lifetime Value (CLTV) Prediction Project

## 🚀 Overview
This project focuses on predicting Customer Lifetime Value (CLTV) using historical transactional data. Understanding CLTV is crucial for businesses to identify their most valuable customers and tailor marketing strategies effectively.

## ✨ Features
- **Data Preprocessing**: Handling raw transactional data, cleaning, and preparing it for analysis.
- **Feature Engineering**: Implementing RFM (Recency, Frequency, Monetary) analysis to derive key customer behavior metrics.
- **Predictive Modeling**: Training a robust machine learning model (XGBoost) to forecast CLTV.
- **Model Evaluation**: Assessing model performance using standard metrics like MAE and RMSE.
- **Data Visualization**: Generating insightful plots to understand customer distributions and model predictions.

## 🛠️ Tools Used
- **Python**: The core programming language for data manipulation, modeling, and visualization.
  - `pandas`: For data handling and preprocessing.
  - `scikit-learn`: For machine learning utilities (e.g., `train_test_split`, `mean_absolute_error`, `mean_squared_error`).
  - `xgboost`: For building the predictive regression model.
  - `matplotlib` & `seaborn`: For creating compelling data visualizations.
  - `joblib`: For saving and loading the trained machine learning model.
- **Excel**: Used for the original dataset format.

## 📊 Deliverables
- `Python_notebook.py`: The main Python script containing all steps from data preprocessing to model training and visualization.
- `cltv_model.joblib`: The trained XGBoost regression model.
- `rfm_distributions.png`: Visualizations showing the distribution of Recency, Frequency, and Monetary values.
- `actual_vs_predicted_cltv.png`: A scatter plot comparing actual vs. predicted CLTV values.
- `Final_LTV_prediction.csv`: A CSV file containing RFM features and the predicted CLTV for each customer.
- `project_report.pdf`: A comprehensive report detailing the project methodology, results, and conclusions.

## 🚀 Getting Started
To run this project locally, ensure you have Python installed along with the libraries mentioned in the `Tools Used` section. You can then execute the `Python_notebook.py` script.

```bash
python Python_notebook.py
```

## 📄 License
This project is open-source and available under the MIT License.

## 📞 Contact
For any questions or collaborations, feel free to reach out.


