# Calfornia-Housing-ML
Machine learning regression on California Housing data.

## Project Overview
This project focuses on predicting housing prices in California using the California Housing dataset provided by scikit-learn. The dataset includes features such as median income, house age, average rooms, population, and proximity to the ocean, among others, to model housing prices in various districts.

## Models used
This project tested several regression models, including Lasso, Ridge, Elastic Net, Random Forest, Gradient Boosting, and XGBoost. After evaluation, XGBoost was selected as the best-performing model due to its superior accuracy and error metrics on the California Housing dataset.

## Dependencies
To run this project, you need the following Python libraries installed:

NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
XGBoost

## Usage
1. Clone the repository or download the project files to your local machine.
2. Ensure all required dependencies are installed (see the **Installation** section).
3. Open the Jupyter Notebook file (`california_housing_analysis.ipynb`) in your preferred environment.
4. Run the notebook cells sequentially to:
   - Load and preprocess the data.
   - Train and evaluate multiple regression models.
   - View the results and performance metrics of the best model (XGBoost).

Feel free to modify the code or parameters to explore different configurations and analyses!

## Results
The XGBoost Regressor outperformed all other models in predicting housing prices using the California Housing dataset. It achieved the highest model.best_score_ of 0.8494, indicating superior cross-validation performance. Additionally, XGBoost delivered the best R² and Mean Absolute Error (MAE) metrics, confirming its accuracy and reliability in modeling the data compared to Lasso, Ridge, Elastic Net, Random Forest, and Gradient Boosting models.
