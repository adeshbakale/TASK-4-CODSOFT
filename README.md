# TASK-4-CODSOFT

# Project Goal:
Predict sales by analyzing advertising spending. The dataset has info on spending on TV, Radio, and Newspaper ads, along with sales.

# Key Libraries:
Used libraries: numpy, pandas, matplotlib.pyplot, seaborn, sklearn.model_selection.train_test_split, sklearn.linear_model.LinearRegression.

# Steps:

1.Loaded dataset from "advertising.csv" using pandas.

2.Checked dataset size and stats using df.shape and df.describe().

3.Visualized relationships between ads (TV, Radio, Newspaper) and sales with seaborn.pairplot.

4.Plotted histograms to understand ad spending distribution.

5.Explored ad-sales correlation with heatmap using seaborn.heatmap.

6.Split data into training and testing sets.

7.Trained a linear regression model on training data.

8.Used the model to predict sales based on TV ad spending for the test set.

9.Obtained model coefficients and intercept.

10.Visualized predictions and actual sales with plots.
