# Adversarial Attacks on Time Series Data

We have worked on Adversarial Attacks on Time Series Data as our graduate project.

## Datasets 
We used three datasets for our projects.

* Hourly Energy Consumption in USA from the [Kaggle Datasets](https://www.kaggle.com/robikscube/hourly-energy-consumption)

* EEG Eye State Dataset from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/EEG+Eye+State).

* MNIST dataset

## Conclusion
In this project, we tried to examine the adversarial attacks on time-series data. We had simulated two commonly used
adversarial-attack methods, Fast Gradient Sign Attacks (FGSM) and Basic Iterative Method, on LSTMs for both regression
and classification models. We noted that a small perturbation on the input dataset results in sharp
drops on the accuracy rates of the models, which means that even a state of art ML model, LSTM is vulnerable to
adversarial attacks. We also saw that iteratively simulating attacks results in lower accuracy rates than at
one time. For further studies, this should also take into account.
