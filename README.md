# Iris Flower Classification with K-Nearest Neighbors

## Overview
This Python script demonstrates the use of the K-Nearest Neighbors (KNN) algorithm for classifying Iris flowers based on their features. The dataset used is the famous Iris dataset, which is included in the scikit-learn library. The script loads the dataset, splits it into training and testing sets, scales the features, and then applies the KNN algorithm with different values of k. Finally, it plots the relationship between the values of k and the corresponding testing accuracy.

## Prerequisites
Make sure you have the required libraries installed. You can install them using the following command:

```bash
pip install scikit-learn matplotlib
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/rajinmail/iris-classification.git
cd iris-classification
```

2. Run the script:

```bash
python iris_classification.py
```

## Code Description
- **Load Iris dataset:**
  - Loads the Iris dataset from scikit-learn.

- **Print dataset information:**
  - Prints feature names, target values, and target names.
  - Checks the number of observations and features.

- **Data Splitting:**
  - Splits the data into training and testing sets using the `train_test_split` function.

- **Data Scaling:**
  - Standardizes the features using `StandardScaler`.

- **K-Nearest Neighbors (KNN) Algorithm:**
  - Iterates over different values of k (1 to 15).
  - Trains the KNN classifier, evaluates performance, and prints confusion matrix and classification report.

- **Plotting:**
  - Plots the relationship between the values of k and the corresponding testing accuracy.

- **Retraining with Optimal k:**
  - Chooses the optimal value of k and retrains the model.

- **Testing the Model:**
  - Uses two hand-made data points to test the model and prints the predicted classes.

## Results
The script provides insights into the performance of the KNN algorithm for different values of k and helps in selecting an optimal k value. The final model is then tested with new data points.

Feel free to experiment with the script and modify parameters for further exploration.
