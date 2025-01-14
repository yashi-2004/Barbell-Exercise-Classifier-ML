
# Barbell Exercise Classification and Repetition Counter

## Overview

- This repository showcases a **Machine Learning-based solution** to **classify barbell exercises** and **count repetitions** accurately using **accelerometer and gyroscope** data. 
- The project aims to provide a robust pipeline for processing time-series sensor data, feature engineering, and training models to identify exercises like **bench press, squat, row, overhead press (OHP),** and **deadlift.**

### Features:
- **Exercise Classification**: Classifies common barbell exercises (bench press, squat, row, overhead press, deadlift).
- **Repetition Counting**: Counts the number of repetitions for each exercise based on accelerometer and gyroscope data.
- **Data Processing & Feature Engineering**: Extensive preprocessing, including filtering noise, handling missing data, and calculating set durations.
- **Modeling**: Implements machine learning models such as decision trees, random forests, and other classifiers for predicting exercises and counting repetitions.

---

## Exercise Photos
![Screenshot 2025-01-14 at 2 03 52 PM](https://github.com/user-attachments/assets/852478f8-f33d-4c17-88e4-977b1fa4ae2a)

![graphs](https://github.com/user-attachments/assets/dab4c9b6-1d88-4397-9c17-802751f09e95)


### Exercises Included:
- **Bench Press** 
- **Squat**
- **Row**
- **Overhead Press (OHP)**
- **Deadlift**

---

## Description
- **Data Preprocessing**: This project starts with the raw accelerometer and gyroscope data, processes it to remove noise, and then applies techniques such as **Butterworth low-pass filters** and **Principal Component Analysis (PCA)** for effective feature extraction.
- **Feature Engineering**: Features like frequency, temporal, and cluster-based features are added for better model performance.
- **Modeling and Evaluation**: Various machine learning models (like decision trees) are trained on these features, and hyperparameter optimization is done via **GridSearch** for the best possible classification accuracy.

---

## Dataset

- The dataset used consists of accelerometer and gyroscope data collected during barbell exercises. 
---

## Setup Instructions

1. **Python Installation**:
    - Install Python (preferably 3.7 or later) on your local machine:
      ```bash
      sudo apt-get install python3
      ```

2. **Anaconda Installation**:
    - Install Anaconda to manage your environment and packages:
      ```bash
      # Download Anaconda installer from the official website and install
      ```

3. **Create and Activate Conda Environment**:
    - Create and activate a new conda environment:
      ```bash
      conda create --name exercise-env python=3.7
      conda activate exercise-env
      ```

4. **Install Required Libraries**:
    - Install all the necessary packages using `conda` and `pip`:
      - Install Conda dependencies:
        ```bash
        conda install --name exercise-env --file conda_requirements.txt
        ```
      - Install non-conda packages using `pip`:
        ```bash
        pip install -r pip_requirements.txt
        ```

---

## Usage

1. **Load and Preprocess Data**:
    - Run the script `data_processing.py` to clean and preprocess the raw data.
   
2. **Model Training**:
    - Use `train_model.py` to train the machine learning models for exercise classification and repetition counting.
   
3. **Testing and Evaluation**:
    - Run the testing scripts to evaluate the model's performance on new data.

---

## Contributions

- This repository was developed as a **personal project** aimed at learning and applying machine learning techniques to sensor data.
- The inspiration for this project came from a YouTube tutorial that demonstrated barbell exercise classification and repetition counting. The project served as a foundation to understand the workflow, and I built upon it by applying the concepts learned.
- At the moment, there are no external contributors.

---
