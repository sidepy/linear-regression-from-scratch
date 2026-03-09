# Linear Regression From Scratch (Python)

This project implements **Linear Regression from scratch using Python and NumPy**, without relying on machine learning libraries such as scikit-learn.  
The goal of this project is to understand the mathematical foundations of linear regression and how **gradient descent** is used to train machine learning models.

---

## Project Overview

Linear Regression is one of the most fundamental algorithms in **Machine Learning**.  
Instead of using pre-built libraries, this project builds the algorithm step by step to demonstrate how a model learns from data.

The notebook walks through the complete workflow of training a regression model, including:

- Implementing a Linear Regression class
- Defining the Mean Squared Error loss function
- Training the model using Gradient Descent
- Visualizing the regression line
- Monitoring the training loss
- Evaluating the model on unseen test data

This project is meant to provide a **clear and educational implementation** of how linear regression works internally.

---

## Technologies Used

- Python  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## Project Structure

The notebook is organized into the following sections:

1. Importing required libraries  
2. Implementing the Linear Regression class  
3. Creating and visualizing the dataset  
4. Implementing the Mean Squared Error (MSE) loss function  
5. Training the model using Gradient Descent  
6. Visualizing the learned regression line  
7. Plotting the training loss curve  
8. Evaluating the model on unseen test data  

---

## How the Model Works

The model learns a linear relationship between input features and the target variable using the equation:

y = wx + b

Where:

- **w** represents the weight (slope)
- **b** represents the bias (intercept)

During training, the model minimizes the **Mean Squared Error (MSE)** between predicted values and true values using **Gradient Descent**, updating the parameters iteratively.

---

## Visualizations Included

The notebook includes several visualizations to better understand the model:

- Dataset visualization
- Learned regression line
- Training loss over iterations
- Comparison between predicted and actual values

---

## Learning Goals

This project was created to:

- Understand how **Linear Regression works internally**
- Learn how **Gradient Descent updates model parameters**
- Practice implementing machine learning algorithms without high-level ML libraries
- Build a strong foundation for more advanced machine learning models

---

## Author

**Mohamed Amine Moatadid**

