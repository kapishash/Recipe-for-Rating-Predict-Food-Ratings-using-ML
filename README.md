# Recipe-for-Rating-Predict-Food-Ratings-using-ML

Best Score **0.793**

**Data Source:** [Kaggle Recipe for Rating Dataset](https://www.kaggle.com/competitions/recipe-for-rating-predict-food-ratings-using-ml) competition was hosted by IIT Madras

The above competition is a multiclass classification problem.

Data is imbalanced and bised towards rating 5


Data Distribution
![data distribution](image.png)


Correlation Between Columns
![correlation between values](image-1.png)

Tried and tested on 4 different models
- Logistic Regression
- LinearSvc
- LightGBM
- XGBoost

<br>

**Roc for logistic Regression**
![Roc for logistic Regression](image-2.png)

<br>

**Roc for Linear Svc**
![Roc for Linear Svc](image-3.png)

<br>

**Roc for LightGBM**
![alt text](image-4.png)

Voting Classifier to make prediction on test dataset
![voting model](image-5.png)

got the best score on **0.793**