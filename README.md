# Quasar Classification Project
## Introduction

This repository contains the code and documentation for a machine learning project aimed at classifying astronomical objects into galaxies, quasars, and stars using photometric data from the Sloan Digital Sky Survey (SDSS).

## Project Overview

The project uses two distinct machine learning approaches:

1. **Naive Bayes Classifier**: A traditional machine learning approach using a Naive Bayes classifier to predict the class of astronomical objects.
2. **Deep Neural Network**: A deep learning approach using a neural network to predict the class of astronomical objects.

## Code Structure

The code is organized into the following sections:

* **Data Loading**: Loads the SDSS dataset and preprocesses the data for training and testing.
* **Naive Bayes Classifier**: Implements a Naive Bayes classifier using scikit-learn.
* **Deep Neural Network**: Implements a deep neural network using TensorFlow and Keras.
* **Training and Evaluation**: Trains and evaluates both models using the preprocessed data.

## Requirements

* Python 3.8+
* scikit-learn
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn

## Usage

1. Clone the repository using `git clone https://github.com/your-username/Quasar-Classification-Project.git`
2. Install the required packages using `pip install -r requirements.txt`
3. Run the code using `python main.py`

## Results

The project achieves an accuracy of 92.16% using the Naive Bayes classifier and 93% using the deep neural network. The results are visualized using confusion matrices, ROC curves, and precision-recall curves.

## Contributing

Contributions are welcome! Please submit a pull request with your changes and a brief description of your contribution.
