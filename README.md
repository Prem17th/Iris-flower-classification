# Iris-flower-classification
A simple project of classification for 3 different flowers by using linear regression.

Basically here we have 3 kinds of flowers:-
1: Setosa
2: Versicolor
3: Virginica 

In this program we are classifying these three different flowers using " sepal length ", " sepal width ", petal length ", "petal width ".

first we import the libraries which are " numpy, pandas, matplotlib " and we are taking the dataset called load_iris()

After the dataset is loaded, we separate the data into " X and Y "
We split the data into two different parts:-
- Training
- Testing
 ( We are using training 80%, and for testing 20% )

The KNN predicts the data and comparison is done between the " Actual and Predicted answer " and we fit into X_train and Y_train.

X test is given to the model to make predictions, where it is store in y_pred, at last in this step the predicted answers are compared with the actual answers.
- X= Flower measurements
- Y= Flower species

Then comes the evaluation where a score of accuracy is done, it checks/ calculates how many it got right

Then comes the new flower after testing the model, you give it something completely new.

As in simple way this is how the flow goes:-

- Iris Dataset

- Separate Input (X) and Output (y)

- Split Data into Training and Testing

- Create KNN Model

- Train Model using Training Data

- Predict Test Data

- Evaluate Model

- Give New Flower Measurements

- Predict Flower Species

What I had learnt is :-  " This project helped me to understand how a classification model, and  it learns from taking the existing data and make it to predict for the new data.
