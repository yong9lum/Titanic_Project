# Titanic_Project

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic collided with an iceberg, sinking into one of the most infamous shipwrecks in history. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers & crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this project, I used machine learning to create six base models, to predict whether a person on the Titanic was likely to survive or die. These models are:
1. Logistic Regression
2. Support Vector Machine
3. Multilayer Perceptron
4. Random Forest
5. Gradient Boosting
6. XGBoost

Following which, I created an Ensemble Learning Model, making use of the six models above in an attempt to improve the overall performance. This model was created using VotingClassifier.

Results from the base models show very promising results, with Support Vector Machine producing the lowest accuracy of 78.7% while Gradient Boosting predicted 93.4% of the trainset. The ensemble model produced 91% accuracy.

I made seven submissions, one for every model I tested. The results are as shows:
1. Logistic Regression: 75.8%
2. Support Vector Machine: 76.6%
3. Multilayer Perceptron: 74.2%
4. Random Forest: 76.8%
5. Gradient Boosting: 76.6%
6. XGBoost: 76.3%
7. Voting Classifier Ensemble: 77.5%

Through this, the ensemble model showed that it can improve predictions from the average, and more feature engineering can possibly be done to try to improve the accuracies for all models.

The dataset & challenge can be found here https://www.kaggle.com/c/titanic/overview.
