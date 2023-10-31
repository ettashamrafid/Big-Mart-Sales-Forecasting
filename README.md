# Big-Mart-Sales-Forecasting
Predict sales for BigMart using advanced regression models. Explore Random Forest, Gradient Boosting, Histogram Gradient Boosting, XGBoost, and LightGBM for accurate predictions. Dataset sourced from Kaggle. Dive into the code, experiments, and results to gain insights into sales forecasting.

---

# BigMart Sales Prediction

## Dataset Description:
The dataset includes the following features:
- Item_Identifier
- Item_Weight
- Item_Fat_Content
- Item_Visibility
- Item_Type
- Item_MRP
- Outlet_Identifier
- Outlet_Establishment_Year
- Outlet_Size
- Outlet_Location_Type
- Outlet_Type

The goal of this project was to predict sales based on these features.

## Data Source:
The dataset was obtained from [BigMart Sales Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/shivan118/big-mart-sales-prediction-datasets).

## Machine Learning Models:
Various regression models were implemented, including:
- Random Forest
- Gradient Boosting
- Histogram Gradient Boosting
- XGBoost
- LightGBM

## Evaluation Metric:
The model performance was assessed using the **r^2 score**.

## Results:
Upon evaluation, the following observations were made:
- In the training dataset, Random Forest outperformed other models significantly, showing the highest r^2 score.
- In the test dataset, LightGBM emerged as the top-performing model with a slight margin. Histogram Gradient Boosting secured the second position, followed by Random Forest.

## How to Use:
1. Clone this repository to your local machine.
2. Ensure you have Python and necessary libraries (scikit-learn, xgboost, lightgbm) installed.
3. Run the Jupyter Notebook or Python scripts to train and evaluate the models.
4. Explore the code to understand the preprocessing steps, model training, and evaluation process.

Feel free to experiment with different models or feature engineering techniques to enhance the model's predictive accuracy.

## Acknowledgments:
- Special thanks to Kaggle and the dataset contributor for providing the dataset.

For any questions or inquiries, please contact [ettashamrafid@gmail.com].

---

This README provides a clear overview of your BigMart Sales Prediction project, including dataset details, models used, evaluation metric, results, and instructions on how to use the project. Make sure to replace placeholders like `[your email address]` with the appropriate information before sharing your project publicly.
