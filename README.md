Car Efficiency Prediction
Objective:

This project aims to predict car fuel efficiency (measured in miles per gallon - MPG) using linear regression. By analyzing vehicle attributes such as horsepower, weight, and model year, we determine which factors contribute most to higher fuel efficiency. The insights from this project help car manufacturers design more fuel-efficient vehicles.
Project Workflow:

The project follows these key steps:

    Data Cleaning:
        Missing Value Imputation: Handling missing values in the Horsepower column by imputing the median.
        Outlier Detection: Detecting and capping outliers in key attributes like MPG, Horsepower, and Weight to reduce their impact on the model.
        Multicollinearity Check: Checking for multicollinearity using Variance Inflation Factor (VIF) and removing highly correlated features.

    Model Building:
        A linear regression model is built using features like Horsepower, Weight, Acceleration, Model Year, and whether the car was made in the US.
        The model is evaluated using RMSE (Root Mean Square Error) and R² scores.

    Results:
        The linear regression model achieved an R² score of 0.84, indicating a strong predictive performance.
        Key predictors of MPG include Horsepower, Weight, and Model Year.

    Visualization:
        Boxplots showing outliers before and after capping.
        Correlation matrix for multicollinearity check.
        Scatter plot comparing actual vs. predicted MPG values.

Results:

    R² score: 0.84
    RMSE: 2.92 (average prediction error)
    Key Predictors:
        Horsepower: Negative correlation with MPG.
        Weight: Negative correlation with MPG.
        Model Year: Newer models show higher MPG.

How to Run the Project:

    Clone the repository:
    git clone https://github.com/your-username/car-efficiency-prediction.git
    Open the notebook:
        You can open the car-efficiency-prediction.ipynb notebook in Google Colab or Jupyter Notebook.

    Dataset:
        The dataset car.csv is included in the repository. The notebook is set to load it from the same directory.

    Run the analysis:
        Follow the steps in the notebook to run the project. Each section contains detailed explanations of the steps, including data cleaning, model building, and evaluation.

Files:

    car-efficiency-prediction.ipynb: Jupyter Notebook containing the detailed analysis and linear regression model.
    Car_Manufacturer_Fuel_Efficiency_Paper.pdf: The final APA-formatted report summarizing the findings.
    car.csv: The dataset used for the analysis.

Technologies Used:

    Languages: Python
    Libraries:
        Pandas, NumPy for data handling.
        Matplotlib, Seaborn for visualization.
        Scikit-learn for machine learning and model building.

Conclusion:

The findings from this project provide car manufacturers with actionable insights for designing more fuel-efficient vehicles by optimizing key attributes such as horsepower and weight. These insights can contribute to reducing fuel consumption and meeting the growing demand for eco-friendly vehicles.
