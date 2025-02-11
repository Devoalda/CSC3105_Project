# README

## Project Overview

This Python notebook is a comprehensive machine learning project that performs data preprocessing, feature engineering, model training, and model evaluation. It uses various machine learning algorithms such as Random Forest, Support Vector Machine (SVM), Logistic Regression, Gradient Boosting, K-Nearest Neighbors (KNN), Naive Bayes, K-Means Clustering, Convolutional Neural Network (CNN), and Multi-Layer Perceptron (MLP) for classification tasks. The project also includes data visualization and model performance evaluation.

## Getting Started

### Prerequisites

- Python 3.7 or later
- pip (Python Package Installer)

### Virtual Environment Setup

It's recommended to create a virtual environment to keep the dependencies required by this project separate from your other Python projects.

For Unix or MacOS, run:

```bash
python3 -m venv env
```

For Windows, run:

```bash
py -m venv env
```

This will create a new virtual environment in a folder named `env`.

To activate the virtual environment, on Unix or MacOS, run:

```bash
source env/bin/activate
```

On Windows, run:

```bash
.\env\Scripts\activate
```

### Dependencies Installation

After activating the virtual environment, you can install the necessary dependencies by running:

```bash
pip install -r requirements.txt
```

This command installs all the necessary libraries used in this project, including:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow

## Usage

After setting up the environment and installing the dependencies, you can start the Jupyter notebook by running:

```bash
jupyter notebook
```

Then, navigate to the notebook file (.ipynb) in the Jupyter notebook web interface and open it.

## Notebook Structure

The notebook is structured as follows:

1. **Data Loading and Cleaning**: The notebook starts by loading the data from a pickle file. If the file doesn't exist, it loads the data from a dataset directory, cleans it, and saves it to a pickle file.

2. **Data Visualization**: The notebook visualizes the data using various plots.

3. **Model Training and Evaluation**: The notebook trains various machine learning models on the data and evaluates their performance. It also saves the trained models to a file for future use.

4. **Model Visualization**: The notebook visualizes the performance of the trained models using various plots and metrics.


## Notebook Files Overview

Here is a brief description of each Jupyter notebook file included in this project:

1. **Project.ipynb**: The primary method utilized for submission is showcased in this notebook, which outlines the outcomes of applying wavelet transformation to the data. This technique enables the analysis of various frequencies of a signal across different scales, aiding in the identification of patterns that change over time.

2. **Project_DFT.ipynb**: This notebook contains the results of applying a Discrete Fourier Transform (DFT) to the data. The DFT is used to transform the data from the time domain to the frequency domain, which can reveal important patterns and features in the data.

3. **Project_Original.ipynb**: This notebook contains the analysis performed on the raw Channel Impulse Response (CIR) data. Unlike the other notebooks, it does not apply transformations such as wavelet or DFT to the data. Instead, it works directly with the original, untransformed data, providing a baseline for comparison with the transformed data.

4. **Project_OLD.ipynb**: This notebook contains our initial approach to the project. It serves as a record of our early ideas and experiments, and may contain different methods and techniques compared to the final approach.