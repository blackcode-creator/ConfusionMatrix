# Confusion Matrix 🛰️ 🤞
A Confusion matrix is a figure or a table that is used to describe the performance of a classifier. It is usually extracted from a test dataset for which the ground truth is known. We compare each class with every other class and see how many samples are misclassified.

Let's consider a binary classification case
where the output is either 0 or 1:

1. True positives: These are the samples for which we predicted 1 as the output and the ground truth is 1 too.
2. True negatives: These are the samples for which we predicted 0 as the output and the ground truth is 0 too.
3. False positives: These are the samples for which we predicted 1 as the output but the ground truth is 0. This is also known as a Type I error.
4. False negatives: These are the samples for which we predicted 0 as the output but the ground truth is 1. This is also known as a Type II error.


For example, in a biometric identification system, it
is very important to avoid false positives, because the wrong people might get access to
sensitive information. Let's see how to create a confusion matrix.

![Screenshot from 2022-06-22 15-46-42](https://user-images.githubusercontent.com/67967749/175035523-12df950e-f249-4ced-bbb6-8180ac4c1da5.png)

