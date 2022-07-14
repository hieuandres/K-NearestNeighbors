## 1.Introduce
### K-nearest Neighbor is a Non parametric ,lazy and supervised machine learning algorithm used for both Classification and Regression.
### Uses the phenomenon “similar things are near to each to each other” .
### It predicts the class of the new data point by majority of votes of k nearest neighbors based on the similarity measure(ie., distance functions).
### Varying the value of K ,differs the prediction class.
### It is commonly used for its easy of interpretation and low calculation time.
## 2.Implementation of KNN from scratch
### Step 1: Compute the Euclidean distance between the test data point and all the training data .
### Step 2: Sort the calculated distances in ascending order .
### Step 3: 1Get the k nearest neighbors by taking top k rows from sorted array
### Step 4: Find the majority class of these rows .
### Step 5: Return predicted class.
### Step 6: Finding accuracy score to make sure the prediction is correct or not.
