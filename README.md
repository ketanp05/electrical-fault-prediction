# Electrical Fault Prediction

This repository contains the code and analysis for the project on predicting electrical faults using machine learning techniques, specifically Recursive Feature Elimination (RFE) and Logistic Regression. The project aims to identify critical features that contribute to electrical faults and predict potential failures to enhance maintenance decisions and reduce outage times.

## Project Overview

The dataset used in this project includes data from an electrical power distribution system, focusing on attributes like power, self-protection measures, ground discharge density, and client characteristics. We apply RFE to select the most significant features and Logistic Regression to model the likelihood of fault occurrences.

## Contents

- `data/`: Folder containing the dataset used in the analysis.
- `notebooks/`: Jupyter notebooks with the detailed analysis and model development.
- `src/`: Source code for the feature selection and logistic regression model.
- `requirements.txt`: List of libraries necessary to run the code.

## Installation

To set up your environment to run the code, you can use the following commands:

```bash
git clone https://github.com/you/Electrical-Fault-Prediction.git
cd Electrical-Fault-Prediction
pip install -r requirements.txt
```

## Usage

Navigate to the `notebooks/` directory and launch the Jupyter notebooks to see the step-by-step analysis:

```bash
cd notebooks
jupyter notebook
```

## Contributing

Contributions to the project are welcome!
