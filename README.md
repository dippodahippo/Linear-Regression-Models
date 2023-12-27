# Regression Models Comparison
This Python program compares the performance of different regression models using randomly generated data. It includes Linear Regression, Ridge Regression, and Lasso Regression, evaluates their accuracy using Mean Squared Error (MSE) and R-squared (R^2), and visualizes their fit to the data.

## Requirements
Python 3.x
NumPy (pip install numpy)
scikit-learn (pip install scikit-learn)
Matplotlib (pip install matplotlib)

## Usage
Clone the repository or download the regression_models.py file.
Install dependencies: pip install -r requirements.txt (or install individually)
Run the script: python regression_models.py
Upon execution, the program will generate random data, split it into training and testing sets, train different regression models, evaluate their performance, and plot their fit to the data.

## File Structure
regression_models.py: Main Python script containing the regression models comparison.
README.md: This file providing information about the program.

## Models Compared
Linear Regression: Fits a linear model to the data.
Ridge Regression: Implements Ridge Regression with alpha=0.1.
Lasso Regression: Implements Lasso Regression with alpha=0.1.
## Output
The program will print the MSE and R^2 scores for each model on the test data. Additionally, it will save a plot (regression_models_plot.png) showing the generated data along with the regression lines for each model.

## Additional Notes
Experiment with different hyperparameters or models to observe their effects on performance.
Modify the generated data size or distribution to test the models on varied datasets.
Explore other evaluation metrics to gain a deeper understanding of model performance.
## Contributors
Diptorshi Tripathi
