# Operationalizing an AWS ML Project

In this project, we'll start with a completed ML project. Our goal in this project will be to use several important tools and features of AWS to adjust, improve, configure, and prepare the model we started with for production-grade deployment.

**Note**: This repository relates to AWS Machine Learning Engineer nanodegree provided by Udacity.

Taking raw ML code and preparing it for production deployment is a common task for ML engineers, and it's very important for the following reasons:

1. ML code alone isn't sufficient for most business scenarios. Real business situations require ML code to integrate 
with other infrastructures, like API's, applications, or other websites that require ML code to be correctly configured.
2. If ML code is deployed in a way that's not optimal, it can lead to cost overruns or bad performance.
3. When ML code is moved to production deployment, security is always a concern, since poor security can lead to data 
leaks or performance issues. 

## Summary Keyword

- Scenario: Use the solution of last project
  - Task: Dog Breed Image Classification
  - Dataset: [Dog Images Breed Dataset](https://325c7m-my.sharepoint.com/:f:/g/personal/khangtictoc_325c7m_onmicrosoft_com/EpD704qbm79IsoZbkXQ042QBv4vwAowXgX9fyta6UV3IuA?e=41eM5c)
- AWS Service:
  - Sagemaker
  - EC2
  - IAM
  - S3
  - Lambda
- Technical tasks:
  - Hyperparameter Tuning
  - Multi-instance training
  - Concurrency and Autoscaling on Lambda
  - Deal with security in working space
  
## Report

The final report is available at [here](report/README.md)