# Adversarial Attacks on Time Series Data

We have worked on Adversarial Attacks on Time Series Data as our graduate project. In this project, we tried to examine the 
adversarial attacks on time-series data. We had simulated two commonly used adversarial-attack methods, Fast Gradient Sign 
Attacks (FGSM) and Basic Iterative Method, on LSTMs for both regression and classification models. We noted that a small 
perturbation on the input dataset results in sharp drops on the accuracy rates of the models, which means that even a state
of art ML model, LSTM is vulnerable to adversarial attacks. We also saw that iteratively simulating attacks results in lower 
accuracy rates than at one time. For further studies, this should also take into account.

## Datasets 
We used three datasets for our projects.

* **Univariate Regression:** Hourly Energy Consumption in the USA from the [Kaggle Datasets](https://www.kaggle.com/robikscube/hourly-energy-consumption)

* **Univariate Classification:** EEG Eye State Dataset from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/EEG+Eye+State).

* **Multivariate Classification:** MNIST dataset

## Python Packages
Here are python packages that we used during the implementation. Our project should be run after installing these packages.

* Numpy
* Pandas
* Sklearn
* matplotlib
* os
* tensorflow.keras
* Tensorflow

## Results

#### 1. Univariate Regression Results:
Here are plots for regression model

![regression](https://user-images.githubusercontent.com/32341138/87667272-baa81c00-c772-11ea-8e38-61698f9805e4.png)


#### 2. Univariate Classification Results:
Here are the results of eye-state prediction project

![eye state](https://user-images.githubusercontent.com/32341138/87659807-c0980000-c766-11ea-8dea-48c41d9c4da5.png)


#### 3. Multivariate Classification Results:
Here are the results of handwritten-digit prediction project

&nbsp;&nbsp;&nbsp;Predictions without applying an attack

![mnist-original](https://user-images.githubusercontent.com/32341138/87659208-e53fa800-c765-11ea-9db6-c30271f78b25.png)


&nbsp;&nbsp;&nbsp;Predictions after applying attacks
  
![mnist](https://user-images.githubusercontent.com/32341138/87659075-b0335580-c765-11ea-8d6e-64e83feb1462.png)



