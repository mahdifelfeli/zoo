# Zoo Animal Classification 🦁

A machine learning project to classify animals into 7 different classes based on their attributes using the "Zoo" dataset. This project uses a K-Nearest Neighbors (KNN) classifier implemented with Scikit-learn.



---

## Overview

This notebook goes through the complete machine learning pipeline:
1.  **Data Loading:** Reading the `zoo.csv` dataset.
2.  **Exploratory Data Analysis (EDA):** Analyzing the features, checking for null values, and visualizing the distribution of the target variable (`class_type`).
3.  **Data Cleaning:** Identifying and dropping duplicate entries.
4.  **Model Training:** * Splitting the data into training and testing sets.
    * Training a **K-Nearest Neighbors (KNN)** classifier.
5.  **Model Evaluation:** * Achieving a **~96% accuracy** on the test set.
    * Generating a confusion matrix and a detailed classification report.
6.  **Hyperparameter Tuning:** Finding the optimal value for 'K' (number of neighbors) by testing values from 1 to 25 and plotting their accuracy.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)

---

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mahdifelfeli/zoo.git](https://github.com/mahdifelfeli/zoo.git)
    cd zoo
    ```

2.  **Create a virtual environment and install dependencies:**
    ```bash
    # Create environment
    python -m venv venv
    # Activate (Windows)
    .\venv\Scripts\activate
    # Activate (macOS/Linux)
    source venv/bin/activate
    
    # Install libraries
    pip install -r requirements.txt
    ```

3.  **Run the Notebook:**
    * The `zoo.csv` file is included in the repository.
    * Open and run the `zoo_v1.ipynb` notebook using Jupyter:
    ```bash
    jupyter notebook
    ```
