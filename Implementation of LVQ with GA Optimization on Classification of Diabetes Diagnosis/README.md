# Implementation of Learning Vector Quantization (LVQ) with Genetic Algorithm (GA) Optimization on Classification of Diabetes Diagnosis

## Introduction
This project was completed as the final project for the Computational Intelligence class. Our team consisted of seven members, and I was the team leader. Our task was to implement the LVQ algorithm with GA optimization for the classification of diabetes diagnosis.

## Motivation
Diabetes is a widespread chronic disease that affects millions of people worldwide. One of the most critical challenges in diabetes diagnosis is to determine the type of diabetes that a patient has. This project aims to implement the LVQ algorithm with GA optimization to classify diabetes diagnosis accurately.

## Data
The dataset for this project was provided by our lecturer. It contained various features related to diabetes diagnosis, including glucose level, blood pressure, body mass index, and age.

## Methodology
The LVQ algorithm is a supervised learning algorithm used for classification and clustering. It is a modification of the competitive learning algorithm that maps input vectors to a set of codebook vectors. In this project, we implemented the LVQ algorithm from scratch using Python class.

However, the LVQ algorithm has some weaknesses, such as low accuracy, in some classification cases. Therefore, we employed GA optimization to improve the performance of the LVQ algorithm. GA optimization is a metaheuristic algorithm that uses the principles of natural selection and genetics to search for the optimal solution.

## Results
We compared the accuracy of LVQ with and without GA optimization. The LVQ algorithm achieved an accuracy of 75.73%, while LVQ with GA optimization achieved an accuracy of 79%. The best parameters used for GA optimization included a population size of 100, a crossover rate of 0.9, a probability of mutation of 0.5, 100 generations, a learning rate of 0.001, a decrease learning rate of 0.1, a maximum epoch of 200, and a minimum learning rate of 0.0001.