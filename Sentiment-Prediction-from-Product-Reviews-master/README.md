# Sentiment-Prediction-from-Product-Reviews

The project is based on [Classification Course](https://www.coursera.org/learn/ml-classification/home/welcome) by UW on Coursera.

---
``` logistic regression with built-in module.ipynb ```

Predicting sentiment from product reviews based on Graphlab-Create library using built-in logistic regression module.

The goal of this first notebook is to **explore logistic regression and feature engineering with existing GraphLab functions**:
* Use SFrames to do some feature engineering
* Train a logistic regression model to predict the sentiment of product reviews.
* Inspect the weights (coefficients) of a trained logistic regression model.
* Make a prediction (both class and probability) of sentiment for a new product review.
* Given the logistic regression weights, predictors and ground truth labels, write a function to compute the accuracy of the model.
* Inspect the coefficients of the logistic regression model and interpret their meanings.
* Compare multiple logistic regression models.

**Link** to graphlab-create:
**[Graphlab-Create](https://github.com/dato-code/GraphLab-Create-SDK)**

---
``` logistic regression without built-in module.ipynb ```

Predicting sentiment from product reviews based on Graphlab-Create library without using built-in logistic regression module.

This self-coded logistic regression model was trained using **less** words than the model in built-in logistic regression.

The goal of this notebook is to **implementing logistic regression classifier from scratch**:
* Extract features from Amazon product reviews.
* Convert an SFrame into a NumPy array.
* Implement the link function for logistic regression.
* Write a function to compute the derivative of the log likelihood function with respect to a single coefficient.
* Implement gradient ascent.
* Given a set of coefficients, predict sentiments.
* Compute classification accuracy for the logistic regression model.

---
```logistic regression with L2 regularization```

The goal of this second notebook is to implement self-coded logistic regression classifier with L2 regularization:
* Extract features from Amazon product reviews.
* Convert an SFrame into a NumPy array.
* Write a function to compute the derivative of log likelihood function with an L2 penalty with respect to a single coefficient.
* Implement gradient ascent with an L2 penalty.
* Empirically explore how the L2 penalty can ameliorate overfitting.

---
```precision and recall```

The goal of this second notebook is to understand precision-recall in the context of classifiers:
 * Use Amazon review data in its entirety.
 * Train a logistic regression model.
 * Explore various evaluation metrics: accuracy, confusion matrix, precision, recall.
 * Explore how various metrics can be combined to produce a cost of making an error.
 * Explore precision and recall curves.
