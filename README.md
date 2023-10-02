# Bank Notes Authentication Project

This repository contains Python code and resources for a banknote authentication project. The project focuses on the classification and verification of banknotes as either genuine or counterfeit based on various features extracted from images of the banknotes.

## Overview

Banknote authentication is a crucial task in the financial industry to prevent the circulation of counterfeit currency. This project aims to create a predictive model that can accurately distinguish between genuine and counterfeit banknotes, ensuring the security of financial transactions.

## Dataset

The dataset used in this project can be found attached to the code files in the repository. It consists of features extracted from images of banknotes. The main features include:

- `Variance`: Variance of wavelet-transformed image
- `Skewness`: Skewness of wavelet-transformed image
- `Curtosis`: Curtosis of wavelet-transformed image
- `Entropy`: Entropy of image
- `Class`: Binary label indicating whether the banknote is genuine (Class 0) or counterfeit (Class 1)

## Getting Started

Follow these steps to get started with the project:

### Prerequisites

Before running the code, ensure you have the required Python libraries installed. You can install them using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### Code

Clone this repository to your local machine:

```bash
git clone https://github.com/AdityaJak/Banknote_Authentication.git
```

Navigate to the project directory:

```bash
cd Banknote_Authentication
```

### Usage

1. Open the Jupyter Notebook file `banknotes.ipynb`.

2. Execute the code cells in the notebook to perform the following tasks:
   - Data loading and preprocessing.
   - Exploratory data analysis (EDA) to understand the dataset.
   - Feature selection and engineering.
   - Building and training predictive models for banknote authentication.
   - Model evaluation and performance metrics.

3. Customize the notebook to fit your specific requirements or experiment with different machine learning algorithms.

## Results and Evaluation

The project evaluates the predictive models using various metrics such as accuracy, precision, recall, and F1-score to determine their effectiveness in authenticating banknotes.

## Acknowledgments

- This project is for educational purposes and should not be used as the sole basis for financial decisions.
- Always consult with financial experts and use professional authentication methods in real-world scenarios.

## Author

[Adithya Jakkaraju]

Feel free to reach out with any questions or suggestions!

I hope this project contributes to the prevention of counterfeit banknotes and enhances financial security. Thank you for your interest and support!
