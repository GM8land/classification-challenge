
## Module 13 Challenge: Create and compare 2 classification models (Logistic Regression, Random Forest Classifier)to detect spam emails
### Instructions:
Let's say you work at an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.
This challenge consists of the following subsections:
- Split the data into training and testing sets.
- Scale the features.
- Create a logistic regression model.
- Create a random forest model.
- Evaluate the models.
### Requirements
- Split the Data into Training and Testing Sets (30 points)
  - There is a prediction about which model you expect to do better. (5 points)

  - The labels set (y) is created from the “spam” column. (5 points)

  - The features DataFrame (X) is created from the remaining columns. (5 points)

  - The value_counts function is used to check the balance of the labels variable (y). (5 points)

  - The data is correctly split into training and testing datasets by using train_test_split. (10 points)

- Scale the Features (20 points)
  - An instance of StandardScaler is created. (5 points)

  - The Standard Scaler instance is fit with the training data. (5 points)

  - The training features DataFrame is scaled using the transform function. (5 points)

  - The testing features DataFrame is scaled using the transform function. (5 points)

- Create a Logistic Regression Model (20 points)
  - A logistic regression model is created with a random_state of 1. (5 points)

  - The logistic regression model is fitted to the scaled training data (X_train_scaled and y_train). (5 points)

  - Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable. (5 points)

  - The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function. (5 points)

- Create a Random Forest Model (20 points)
  - A random forest model is created with a random_state of 1. (5 points)

  - The random forest model is fitted to the scaled training data (X_train_scaled and y_train). (5 points)

  - Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable. (5 points)

  - The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function. (5 points)

- Evaluate the Models (10 points)
The following questions are answered accurately:

  - Which model performed better? (5 points)

  - How does that compare to your prediction? (5 points)


### Grade: 100
### Feedback from Grader:
Hello Geoff, 



Thanks for your submission. 



Great work on your Jupyter notebook! 



You’ve done an excellent job splitting the data, scaling the features, and building and evaluating both the logistic regression and random forest models. 



Your code is clean and accurate, and you correctly identified the better-performing model. 



However, your initial prediction could use a bit more detail, and the final comparison could be more thorough. I have not deducted any points since you have answered the questions correctly. 



I would suggest you make use of your README file by writing a short report, providing context to your work and citing any sources used. 



Overall, you’ve demonstrated a solid understanding of the process and delivered a well-done analysis. Keep it up!



Best,

Grader FF
Central Grader , Aug 7, 2024 at 10:20am
