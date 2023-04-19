# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 10129

Number of Attributes: 16

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
Best Accuracy =  0.92 Best Kernel =  rbf Best Nu =  4.41 Best Epsilon =  0.51
Best Accuracy =  0.95 Best Kernel =  linear Best Nu =  5.95 Best Epsilon =  1.01
Best Accuracy =  0.96 Best Kernel =  linear Best Nu =  4.63 Best Epsilon =  0.77
Best Accuracy =  0.86 Best Kernel =  poly Best Nu =  2.27 Best Epsilon =  3.24
Best Accuracy =  0.84 Best Kernel =  linear Best Nu =  5.13 Best Epsilon =  6.63
Best Accuracy =  0.85 Best Kernel =  rbf Best Nu =  2.37 Best Epsilon =  1.3
Best Accuracy =  0.95 Best Kernel =  linear Best Nu =  2.17 Best Epsilon =  6.28
Best Accuracy =  0.82 Best Kernel =  rbf Best Nu =  2.9 Best Epsilon =  4.31
Best Accuracy =  0.91 Best Kernel =  poly Best Nu =  6.32 Best Epsilon =  6.61
Best Accuracy =  0.93 Best Kernel =  linear Best Nu =  0.21 Best Epsilon =  5.63

## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 3 has the best accuracy of 0.96 having kernel = linear, Nu = 4.63 and Epsilon = 0.77.

## Written By
Name : Pulkit Bhatia
  
Roll No. : 102003306

Sub-Group: 3CO12
