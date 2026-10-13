# House Sales Analysis and Price Prediction

## Project Overview

This project analyzes residential property sales data from King County, Washington, USA, to explore factors associated with house prices and build regression models for price prediction.

Using Python and machine learning libraries, the project covers data exploration, data cleaning, visualization, regression modeling, and model evaluation.

## Objectives

- Explore housing data and understand its key features.
- Prepare the dataset for analysis.
- Analyze relationships between property characteristics and house prices.
- Build regression models to predict house prices.
- Evaluate model performance using the R² score.

## Dataset

The dataset contains residential property sales information from King County, Washington, covering May 2014 to May 2015.

**Dataset source:** [King County House Sales Prediction — Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

Some features include:

- `price` — Sale price of the property
- `bedrooms` — Number of bedrooms
- `bathrooms` — Number of bathrooms
- `sqft_living` — Interior living area in square feet
- `sqft_lot` — Lot size in square feet
- `floors` — Number of floors
- `waterfront` — Waterfront status
- `grade` — Overall grade of the property
- `lat` and `long` — Geographic coordinates

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Load the dataset into a Pandas DataFrame.
2. Inspect the dataset, data types, and descriptive statistics.
3. Clean and prepare the data.
4. Perform exploratory data analysis and visualization.
5. Build linear and multiple linear regression models.
6. Apply polynomial regression pipelines.
7. Evaluate Ridge Regression and Polynomial Ridge Regression using R² scores.

## Models Used

- Linear Regression
- Multiple Linear Regression
- Polynomial Regression Pipeline
- Ridge Regression
- Polynomial Ridge Regression

## How to Run

1. Download or clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Place `kc_house_data.csv` in the same directory as the notebook.
4. Open the notebook in Jupyter Notebook or VS Code.
5. Run the notebook cells sequentially.

## Evaluation

Model performance is evaluated using the coefficient of determination (R² score). Refer to the executed notebook for the actual scores and model outputs.

## Conclusion

This project demonstrates how data analysis, visualization, and regression techniques can be applied to housing data to investigate factors associated with property prices and build house price prediction models.

## Acknowledgment

This project was completed as part of the IBM/Coursera Data Analysis with Python course. The original guided assignment was used as the starting point, and the notebook was organized for presentation in a GitHub portfolio.

## Author

Muskan
