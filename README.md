# ML-Classifier-comparison-on-multinomial-data

This project was created as a part of university assessments the following is a brief explaination on the project.

INTRODUCTION

a. Aim and Objective

The goal of this report is to exploit various machine learning classification-based algorithms to perform a multi-level classification of the data provided. The data is provided into 2 sets training and testing data. The training data contains about 30,000 samples with the labels provided for the classification and the testing data contains about 5000 samples with no label. The goal is to classify and provide the labels for the testing data. The assignment forces you inculcate into critical thinking and analytical skills by making you perform various classification algorithms on the same data and understand what is working for the data and what can you do to improve the classification. It is like a lot of real-world implementations of machine learning based classification algorithms. We can also divide the goal and scope of the assignment on a microscopic level as:
• Learning about the data set
• Identifying Pre-processing techniques that would help enhance the classification
• Determining the classifiers to be used for the given classification problem
• Fine tuning the parameters of these classifiers
• Comparing the performance of the various classifiers implemented
• Obtaining the best possible predicted labels for the given test dataset.

a. Understanding the Dataset

The dataset consists of grayscale images of the size 28x28 that can be classified into aset of categories. The dataset consists of a training set of 30,000 examples and a test set of 5,000 examples belonging to these 10 categories.
The training dataset 30000 samples contains both the feature and label in the data, however upon inspection it is found that the testing dataset does not have any labels. So, for the purpose of understanding the accuracy of the classification models the training data is split into training and testing data into a ratio of 75% training (22500 samples) and 25% testing (7500 samples). Eventually the working model will be implemented on the final
output test data (5000 samples) to predict test labels.
