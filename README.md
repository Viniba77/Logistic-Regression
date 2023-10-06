# Diff between Linear Regression and Logistic-Regression

Linear and logistic regression are both commonly used statistical methods in machine learning and statistics, but they serve different purposes and are applied to different types of problems. Here's a brief overview of the differences between the two:

1. **Type of Output**:
   - **Linear Regression**: Linear regression is used when the dependent variable (output) is continuous and numeric. It predicts a value on a continuous scale, such as predicting a person's salary, house price, or temperature.
   - **Logistic Regression**: Logistic regression is used when the dependent variable is categorical and represents binary outcomes (0 or 1). It predicts the probability that a given input belongs to a particular category or class.

2. **Equation and Hypothesis**:
   - **Linear Regression**: In linear regression, the goal is to find a linear relationship between the independent variables (input features) and the dependent variable. The equation for linear regression is a simple linear equation: y = mx + b, where y is the predicted value, x is the input feature, m is the slope, and b is the intercept.
   - **Logistic Regression**: In logistic regression, the goal is to find the best-fitting S-shaped curve (sigmoid) that models the probability of a binary outcome. The logistic function transforms the linear combination of input features into a value between 0 and 1, representing the probability of the positive class.

3. **Output Interpretation**:
   - **Linear Regression**: In linear regression, the output represents the expected or predicted value of the continuous dependent variable. For example, a linear regression model predicting salary might output a predicted salary value.
   - **Logistic Regression**: In logistic regression, the output represents the probability that an input belongs to a specific class (usually the positive class). It is often used to make binary classifications based on a threshold, where values above the threshold are classified as one class, and values below are classified as the other class.

4. **Loss Function**:
   - **Linear Regression**: The loss function used in linear regression is often the Mean Squared Error (MSE), which measures the average squared difference between predicted and actual values.
   - **Logistic Regression**: The loss function used in logistic regression is typically the Log-Loss or Cross-Entropy loss, which measures the difference between predicted probabilities and actual class labels.

5. **Example Applications**:
   - **Linear Regression**: Predicting house prices based on features like square footage, number of bedrooms, etc.
   - **Logistic Regression**: Predicting whether an email is spam or not spam, predicting whether a customer will buy a product or not based on certain features.

In summary, linear regression is used for predicting continuous numeric values, while logistic regression is used for binary classification problems, where the output is a probability estimate that an input belongs to a particular class.
