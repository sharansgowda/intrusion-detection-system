# Intrusion Detection System

## Overview

This project implements an **Intrusion Detection System (IDS)** using various machine learning algorithms. The goal is to classify network traffic as either "normal" or "malicious" to detect potential cyber-attacks.

## Key Features

  * **Data Preprocessing**: Cleans and prepares the dataset for model training.
  * **Machine Learning Models**: Uses classifiers such as **Decision Tree**, **Gaussian Naive Bayes**, and **XGBoost**.
  * **Ensemble Learning**: Combines the predictions of multiple classifiers to improve accuracy.

## Installation

1.  **Clone the repository**:

    ```bash
    git clone https://github.com/sharansgowda/intrusion-detection-system.git
    cd intrusion-detection-system
    ```

2.  **Create a virtual environment** (recommended):

    ```bash
    virtualenv venv
    source venv/bin/activate
    ```

3.  **Install the required packages**:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Download the dataset** (e.g., KDD Cup 1999) and place it in the project directory.
2.  Run the main script or Jupyter notebook to train and evaluate the models.


