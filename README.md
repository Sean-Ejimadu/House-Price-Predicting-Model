# House-Price-Predicting-Model

**Project Focus:**

*Built a model that predicts house prices based on city.*

**Cleaning the Data:**

I performed data wrangling to clean and prepare the dataset, utilizing functions such as dropna() to handle missing values, astype() for data type conversion etc.

**Model Selection:**

I chose Ridge Regression due to its ability to handle multicollinearity by introducing a regularization term, which penalizes large coefficients and helps improve generalization.

**Model Evaluation:**

The model was evaluated using Mean Absolute Error (MAE), which provided a clear interpretation of the average error in predicted house prices.
With a training MAE less than my baseline MAE it suggested that my model is effective at reducing error compared to a naive model.

**Conclusion:**

The Ridge Regression model successfully reduced overfitting and provided accurate house price predictions based on the city, with MAE offering a straightforward evaluation of the model’s performance.
