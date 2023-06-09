# MLzoomcamp

# SYLLABUS

- Introduction to Machine Learning
- Machine Learning for Regression
- Machine Learning for Classification
- Evaluation Metrics for Classification
- Deploying Machine Learning Models
- Decision Trees and Ensemble Learning
- Neural Networks and Deep Learning
- Serverless Deep Learning
- Kubernetes and TensorFlow Serving

# CHAPTERS

## 1. Introduction to Machine Learning

- 1.1 Introduction to Machine Learning

<img src = "imgs/01-01.jpg" width=80% height=80%> 

- 1.2 ML vs Rule-Based Systems

<img src = "imgs/01-02.jpg" width=80% height=80%>  

- 1.3 Supervised Machine Learning  
    
<img src = "imgs/01-03.jpg" width=80% height=80%>  

- 1.4 CRISP-DM  
    
<img src = "imgs/01-04.jpg" width=80% height=80%>  

- 1.5 Model Selection Process  
    
<img src = "imgs/01-05.jpg" width=80% height=80%>  

- 1.6 Setting up the Environment
- 1.7 Introduction to NumPy  
[Introduction to NumPy (notebook)](https://github.com/aziart/mlzoomcamp/blob/main/01-07%20-%20Introduction%20to%20NumPy.ipynb)

- 1.8 Linear Algebra Refresher  
[Linear Algebra Refresher (notebook)](https://github.com/aziart/mlzoomcamp/blob/main/01-08%20-%20Linear%20Algebra%20Refresher.ipynb)
    
<img src = "imgs/01-08.jpg" width=80% height=80%>  

- 1.9 Introduction to Pandas  
[Introduction to Pandas (notebook)](https://github.com/aziart/mlzoomcamp/blob/main/01-09%20-%20Introduction%20to%20Pandas.ipynb)

## 2. Machine Learning for Regression

> [Car Price Prediction (notebook):](https://github.com/aziart/mlzoomcamp/blob/main/02-01-15%20-%20Car%20Price%20Prediction.ipynb)
> - 2.2 Data preparation  
    <img src = "imgs/02-02.jpg" width=80% height=80%>  
> - 2.3 Exploratory data analysis  
    <img src = "imgs/02-03.jpg" width=80% height=80%>  
> - 2.4 Setting up the validation framework  
    <img src = "imgs/02-04.jpg" width=80% height=80%>  
> - 2.5 Linear regression  
> - 2.6 Linear regression: vector form  
> - 2.7 Training linear regression: Normal equation  
> - 2.8 Baseline model for car price prediction project  
> - 2.9 Root mean squared error  
> - 2.10 Using RMSE on validation data  
> - 2.11 Feature engineering  
> - 2.12 Categorical variables  
> - 2.13 Regularization  
> - 2.14 Tuning the model  
> - 2.15 Using the model  

## 3. Machine Learning for Classification

- 3.1 Churn prediction project
- 3.2 Data preparation
- 3.3 Setting up the validation framework
- 3.4 EDA
- 3.5 Feature importance: Churn rate and risk ratio
- 3.6 Feature importance: Mutual information
- 3.7 Feature importance: Correlation
- 3.8 One-hot encoding
- 3.9 Logistic regression
- 3.10 Training logistic regression with Scikit-Learn
- 3.11 Model interpretation
- 3.12 Using the model
- 3.13 Summary
- 3.14 Explore more
- 3.15 Homework

## 4. Evaluation Metrics for Classification

- 4.1 Evaluation metrics: session overview
- 4.2 Accuracy and dummy model
- 4.3 Confusion table
- 4.4 Precision and Recall
- 4.5 ROC Curves
- 4.6 ROC AUC
- 4.7 Cross-Validation
- 4.8 Summary
- 4.9 Explore more
- 4.10 Homework

## 5. Deploying Machine Learning Models

- 5.1 Intro / Session overview
- 5.2 Saving and loading the model
- 5.3 Web services: introduction to Flask
- 5.4 Serving the churn model with Flask
- 5.5 Python virtual environment: Pipenv
- 5.6 Environment management: Docker
- 5.7 Deployment to the cloud: AWS Elastic Beanstalk (optional)
- 5.8 Summary
- 5.9 Explore more
- 5.10 Homework

## 6. Decision Trees and Ensemble Learning

- 6.1 Credit risk scoring project
- 6.2 Data cleaning and preparation
- 6.3 Decision trees
- 6.4 Decision tree learning algorithm
- 6.5 Decision trees parameter tuning
- 6.6 Ensemble learning and random forest
- 6.7 Gradient boosting and XGBoost
- 6.8 XGBoost parameter tuning
- 6.9 Selecting the best model
- 6.10 Summary
- 6.11 Explore more
- 6.12 Homework

## 7. Production-Ready Machine Learning (Bento ML)

- 7.1 Intro/Session Overview
- 7.2 Building Your Prediction Service with BentoML
- 7.3 Deploying Your Prediction Service
- 7.4 Sending, Receiving and Validating Data
- 7.5 High-Performance Serving
- 7.6 Bento Production Deployment
- 7.7 (Optional) Advanced Example: Deploying Stable Diffusion Model
- 7.8 Summary
- 7.9 Homework

## Midterm Project

## 8. Neural Networks and Deep Learning

- 8.1 Fashion classification
- 8.1b Setting up the Environment on Saturn Cloud
- 8.2 TensorFlow and Keras
- 8.3 Pre-trained convolutional neural networks
- 8.4 Convolutional neural networks
- 8.5 Transfer learning
- 8.6 Adjusting the learning rate
- 8.7 Checkpointing
- 8.8 Adding more layers
- 8.9 Regularization and dropout
- 8.10 Data augmentation
- 8.11 Training a larger model
- 8.12 Using the model
- 8.13 Summary
- 8.14 Explore more
- 8.15 Homework

## 9. Serverless Deep Learning

- 9.1 Introduction to Serverless
- 9.2 AWS Lambda
- 9.3 TensorFlow Lite
- 9.4 Preparing the code for Lambda
- 9.5 Preparing a Docker image
- 9.6 Creating the lambda function
- 9.7 API Gateway: exposing the lambda function
- 9.8 Summary
- 9.9 Explore more
- 9.10 Homework

## 10. Kubernetes and TensorFlow Serving

- 10.1 Overview
- 10.2 TensorFlow Serving
- 10.3 Creating a pre-processing service
- 10.4 Running everything locally with Docker-compose
- 10.5 Introduction to Kubernetes
- 10.6 Deploying a simple service to Kubernetes
- 10.7 Deploying TensorFlow models to Kubernetes
- 10.8 Deploying to EKS
- 10.9 Summary
- 10.10 Explore more
- 10.11 Homework

## 11. KServe (optional)

- 11.1 Overview
- 11.2 Running KServe locally
- 11.3 Deploying a Scikit-Learn model with KServe
- 11.4 Deploying custom Scikit-Learn images with KServe
- 11.5 Serving TensorFlow models with KServe
- 11.6 KServe transformers
- 11.7 Deploying with KServe and EKS
- 11.8 Summary
- 11.9 Explore more

## Capstone Project 1

## Article

## Capstone project 2 (optional)