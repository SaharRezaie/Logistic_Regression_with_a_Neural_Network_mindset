# Logistic Regression with a Neural Network Mindset

## Introduction

This repository contains a Python implementation of a logistic regression model for binary image classification using a neural network mindset. The model classifies images as either "cat" (y=1) or "not cat" (y=0). This README provides an overview of the project, how to use it, and other relevant information.
-------------------------------------------------------
## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Data](#data)
4. [Training](#training)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)
-------------------------------------------------------
## Installation

To use this code, you will need Python 3.x installed on your system. You can clone this repository using Git:

```bash
git clone https://github.com/yourusername/Logistic_Regression_with_a_Neural_Network_mindset.git

cd Logistic_Regression_with_a_Neural_Network_mindset

pip install -r requirements.txt
-------------------------------------------------------
**Usage**
To use the logistic regression model for binary image classification, follow these steps:

1.Data: Prepare your image data and labels. Ensure that your data is formatted correctly (e.g., as NumPy arrays) and labeled as y=1 for "cat" images and y=0 for "not cat" images.

2.Configuration: Modify the configuration parameters in the code as needed, such as learning rate, number of iterations, and model initialization.

3.Training: Run the training script to train the logistic regression model on your data:
python train.py

4.Results: Evaluate the model's performance and examine the results (accuracy, cost, etc.) to determine the effectiveness of your model.
-------------------------------------------------------
**Data**

We attached a file named "lr_utils.py" in which we defined a function named "load_dataset".
The number of our training examples are 209,testing examples are 50.The heigh and weight of the examples are 64 pxls.

-------------------------------------------------------

**Training**

Explain how the training process works, including:
Forward propagation
Cost calculation
Backward propagation (gradient descent)
Parameter updates

-------------------------------------------------------

**Results**
The train accuracy percentage of our code is 91.38755980861244 % which is a good sanity check.The test accuracy percentage of our code is 34.0 %.
For reaching the best result we try different learning rates:
learning rate is: 0.01
train accuracy: 71.29186602870814 %
test accuracy: 34.0 %

learning rate is: 0.001
train accuracy: 74.16267942583733 %
test accuracy: 34.0 %

learning rate is: 0.0001
train accuracy: 66.02870813397129 %
test accuracy: 34.0 %

-------------------------------------------------------
**Contributing**

If you'd like to contribute to this project, please follow these guidelines:
Fork the repository.
Create a new branch for your changes: git checkout -b feature/your-feature-name.
Make your changes and commit them: git commit -m 'Add new feature'.
Push your changes to your fork: git push origin feature/your-feature-name.
Submit a pull request with a clear description of your changes.

-------------------------------------------------------
**License**
This project is licensed under the MIT License. See the LICENSE file for details.

-------------------------------------------------------

**Contact**

Your Name:Sahar Rezaie
Email: sahar38566@gmail.com

Feel free to contact me with any questions or feedback about this project.

