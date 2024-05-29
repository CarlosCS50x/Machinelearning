# Iris Dataset Analysis and Model Evaluation

This repository contains Python code to analyze the famous Iris dataset using machine learning algorithms and evaluate their performance.

## Dataset

The Iris dataset is a classic dataset in the field of machine learning and statistics. It contains 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The goal is to classify the iris flowers into one of three species: Setosa, Versicolor, or Virginica.

The dataset is loaded from the following URL: [Iris Dataset](https://raw.githubusercontent.com/jbrownlee/Datasets/master/iris.csv)

## Code Structure

The Python code in `iris_analysis.py` performs the following tasks:

1. Loads the Iris dataset using pandas.
2. Displays the shape of the dataset and the distribution of classes.
3. Plots histograms for each feature.
4. Generates a scatter plot matrix to visualize the relationships between features.
5. Splits the dataset into training and validation sets.
6. Evaluates various machine learning algorithms using cross-validation:
    - Logistic Regression
    - Linear Discriminant Analysis
    - K-Nearest Neighbors
    - Decision Tree
    - Gaussian Naive Bayes
    - Support Vector Machine
7. Compares the performance of the algorithms using box plots.
8. Trains a Support Vector Machine model on the training set.
9. Makes predictions on the validation set and evaluates the model's performance using accuracy, confusion matrix, and classification report.

## Requirements

- Python 3.12.3
- Libraries: pandas, scikit-learn, matplotlib

## Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/CarlosCS50x/iris-dataset-analysis.git
    ```

2. Navigate to the project directory:

    ```bash
    cd iris-dataset-analysis
    ```

3. Install the required libraries (if not already installed):

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Python script:

    ```bash
    python iris_analysis.py
    ```

