# Fuel Consumption & CO₂ Emission Prediction
### Project Overview

This project demonstrates how to use Scikit-Learn to implement Simple Linear Regression for predicting CO₂ emissions from vehicle characteristics. The dataset used contains details about fuel consumption, engine size, cylinders, and CO₂ emissions.

The project not only builds a predictive model but also provides detailed Exploratory Data Analysis (EDA) to understand how different vehicle features influence emissions.

### Dataset

The dataset used is Fuel Consumption.csv, which includes:

- Engine size (L)

- Cylinders

- Combined (mpg) → Fuel efficiency

- CO2 emissions (g/km)

### Exploratory Data Analysis (EDA)

#### Data Inspection

  Checked structure, summary statistics, and unique values.

  Focused on key features influencing emissions.

#### Visualizations

- Histograms showing the distribution of engine sizes, cylinders, fuel consumption, and emissions.

- Scatter plots & regression plots:

    - Engine size vs CO₂ emissions → Strong positive relationship.

    - Fuel efficiency (mpg) vs CO₂ emissions → Negative relationship (more efficient cars emit less CO₂).

#### Observations

- Most vehicles have smaller engines (1.5L – 3.5L) and 4–6 cylinders.

- Higher fuel efficiency generally corresponds to lower emissions.

- Larger engines with more cylinders contribute significantly to CO₂ emissions.

### Model Implementation

- Used Simple Linear Regression from scikit-learn.

- Trained the model with selected features to predict CO₂ emissions.

- Evaluated model performance with metrics like Mean Absolute Error (MAE) and R² score.

### Key Insights

- Engine size is a strong predictor of emissions — bigger engines usually release more CO₂.

- Fuel efficiency is inversely related to emissions — efficient cars emit less CO₂.

- The model provides a baseline understanding of how car features influence environmental impact.

### Tools & Libraries

- Python

- Numpy & Pandas → Data handling

- Matplotlib & Seaborn → Visualization

- Scikit-Learn → Linear regression model
