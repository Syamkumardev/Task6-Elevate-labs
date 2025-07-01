# Task6-Elevate-labs
This is my task 6 
# 🔍 K-Nearest Neighbors (KNN) Classification – Iris Dataset

## Task Overview
This is Task 6 of the AI & ML Internship.  
The objective is to implement and evaluate a K-Nearest Neighbors classifier using the Iris dataset.


# Steps Performed

1. Loaded the Iris dataset from `sklearn.datasets`
2. Normalized features using `StandardScaler`
3. Split the data into training and test sets
4. Trained a KNN classifier using different values of K (1–10)
5. Evaluated the model using accuracy and confusion matrix
6. Selected the best K value based on highest accuracy



## Results

- Best K value: Replace with your output
- Accuracy: Replace with best model accuracy
- Confusion matrix: See plotted heatmap in notebook



## Interview Questions & Answers

1. How does the KNN algorithm work?  
   It finds the K closest data points (neighbors) and assigns the most common class among them to the test point.

2. How do you choose the right K?  
   By evaluating performance for different values using accuracy or cross-validation.

3. Why is normalization important in KNN?  
   Because KNN uses distance-based calculations which are sensitive to feature scales.

4. What is the time complexity of KNN?  
   O(n × d) during prediction, where n is number of training samples and d is number of features.

5. What are pros and cons of KNN?  
   Pros: Simple, no training time.  
   Cons: Slow at prediction time, sensitive to irrelevant features and noise.

6. Is KNN sensitive to noise?  
   Yes, noisy data or outliers can significantly affect predictions.

7. How does KNN handle multi-class problems?  
   It counts the number of neighbors belonging to each class and picks the majority.

8. What’s the role of distance metrics in KNN?  
   Determines how neighbors are calculated; common metrics include Euclidean, Manhattan, and Minkowski distances.



## Tools Used

- Python
- scikit-learn
- pandas, matplotlib, seaborn



## Files Included

- knn_classifier.ipynb — Full implementation
- README.md — Task summary and answers



## Submission

Push your code and README to a new GitHub repository and submit the link via the form provided in the task.
