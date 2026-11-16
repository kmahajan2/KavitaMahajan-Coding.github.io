---
layout: post
author: Kavita Mahajan
tags: [cscc]
---
# Machine Learning Research Assignment

## What is Machine Learning
Machine learning is a technology that enables a computer to learn patterns from data to predict, recognize objects, identify anomalies, make recommendations etc. without rules explicitly programed. At the heart of this technology is data and mathematical model. Key ingredients for successful use of this technology is clear use case, high quality relevant data and appropriate model. 
For the use case identified, first step is data gathering and preparation i.e. data cleanse, quality, relevant features, validation rules etc. and defining separate data sets training and evaluation. It is important ethical practices are used for data gathering, data sensitivity rules are applied and laws are followed and the data included does not introduce unintended bias. 
Next step is selecting the right algorithm(s) and developing the model. This is an iterative process, depending of nature of the data, problem to be solved, desired outcome accuracy, cost etc. many different algorithms are tried and results evaluated to find the right match. 
Training is next, algorithm uses training data to learn patterns and once trained, we have a model is to use. Different types of training may be used i.e. Supervised, Un Supervised and Reinforcement learning.
In supervised learning, the raw data is labeled and model learns the relationship between the two to classify, identify the pattern.
In unsupervised learning, data is not labeled. In this case, if the data is not numerical its first converted to numerical vectors. Then different methods may be applied to identify the pattern i.e. Clustering – data is plotted to define groups of data points and distance from center of the cluster can be used to find potential outliers; Association – frequency may be used as a  measures, if-then logic can be applied if features frequently appear together. Reducing dimensions and simplifying the features to include is another method.
In Reinforcement learning model starts from blank slate but learns through reward and penalty system which actions will yield better outcome. 
Evaluation of the model using non training, evaluation and monitoring of model performance in real life and adjustments is integral part of model development

## What application of Machine Learning did you discover while researching? How does Machine Learning improve or replace existing solutions? Is the application in development or actively being used by companies/institutions? Describe AT LEAST ONE ethical concern using Machine Learning for this application?
AlphaFold 2, a machine learning model developed by Google, helps with protein modeling by predicting protein 3D structures from amino acid sequence. This is important in new drug development as it allows us to identify protein structures that can bind well or work effectively with enzymes in human body and develop drugs that would heal. For training these models, a free trusted database called Protein Data Bank is used which is a repository of molecular structures of known proteins. Some of the features used in training include sequencing of amino acids, evolutionary relationship between sequences, distance between amino acids; geometry of amino acids etc. In simple terms, algorithm (s) use distance, sequencing, geometric layout etc. between similar proteins to learn relationships between amino acid sequences and 3D structures and how a protein may fold etc. Many labs and pharmaceutical companies like Eli Lilly use this model. The model is a double-edged sword, while it can be used to develop drugs to help society, it can also be used to develop drugs that harm us.
