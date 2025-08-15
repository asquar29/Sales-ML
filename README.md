📊 Advertising Sales Prediction
📌 Overview

This project analyzes an Advertising dataset containing TV, Radio, and Newspaper ad spending, and predicts Sales using regression techniques.
The goal is to understand how different advertising channels influence sales and to create a predictive model.

📂 Dataset

Source: Advertising.csv

Columns:

TV – Advertising budget spent on TV

Radio – Advertising budget spent on Radio

Newspaper – Advertising budget spent on Newspaper

Sales – Resulting product sales

Target Variable: Sales

🛠️ Steps Performed

Importing Libraries

pandas, numpy for data handling

matplotlib, seaborn for visualization

sklearn for model building

Data Loading

Loaded Advertising.csv into a Pandas DataFrame

Checked basic structure with .head() and .info()

Exploratory Data Analysis (EDA)

Visualized relationships between ad spend and sales

Checked for correlations using sns.heatmap

Plotted scatter plots for each advertising medium vs sales

Model Building

Used Linear Regression from sklearn

Split data into training and test sets (train_test_split)

Fitted the model on training data

Predicted sales on test data

Model Evaluation

Calculated R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE)

Plotted Actual vs Predicted Sales graph with perfect prediction line for comparison

📈 Results

The model shows a strong positive correlation between TV advertising and sales.

Radio also contributes significantly, while Newspaper spend has a weaker effect.

The regression model predicts sales with good accuracy (high R² score).

🚀 How to Run

Install dependencies:
```

pip install pandas numpy matplotlib seaborn scikit-learn
```

Place Advertising.csv in the same directory as the notebook.

Open Jupyter Notebook and run:
```

jupyter notebook adver.ipynb
```

Execute cells step-by-step to see the analysis and results.

📌 Future Improvements

Try Polynomial Regression to capture non-linear effects

Apply Regularization (Ridge/Lasso) to handle multicollinearity

Compare with Tree-Based Models (Random Forest, XGBoost)

Perform feature engineering (e.g., interaction terms)
