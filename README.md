# Optimizing an ML Pipeline in Azure

## Overview
This project is part of the Udacity Azure ML Nanodegree.
In this project, we build and optimize an Azure ML pipeline using the Python SDK and a provided Scikit-learn model.
This model is then compared to an Azure AutoML run.

## Summary
This dataset contains data about bank marketing campaigns, it's a classfication exercise to predict if the client will subscribe to a term deposit with the bank. One starts to create and optimize an Scikit Learn Logistic Regression ML pipeline with the HyperDrive tool to optimize the hyperparamaters.
Then one will be comparing with the Auto ML results.

The Hyperdrive best performance was achieved with a pipeline MaxAbsScaler LightGBM (0.9170), 57s.
The AutoML best performance was achieved with a pipeline MaxAbsScaler LightGBM (0.9152), first iteration 31s.

## Scikit-learn Pipeline
**Explain the pipeline architecture, including data, hyperparameter tuning, and classification algorithm.**
The pipeline architecture is the following:

![alt text](https://github.com/Jocker1980/AzureML_Engineer_Nanodegree/blob/main/Images/ml-pipeline.png)



**What are the benefits of the parameter sampler you chose?**

**What are the benefits of the early stopping policy you chose?**

## AutoML
**In 1-2 sentences, describe the model and hyperparameters generated by AutoML.**

## Pipeline comparison
**Compare the two models and their performance. What are the differences in accuracy? In architecture? If there was a difference, why do you think there was one?**

## Future work
**What are some areas of improvement for future experiments? Why might these improvements help the model?**

## Proof of cluster clean up
![alt text](https://github.com/Jocker1980/AzureML_Engineer_Nanodegree/blob/main/Images/Compute_target_del.PNG)

