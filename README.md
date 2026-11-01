# Human Activity Recognition using Hidden Markov Models

## Project Overview
This repository contains a machine learning pipeline that uses continuous smartphone sensor data (Accelerometer and Gyroscope) to recognize and decode human activity states. Using a Continuous Gaussian Hidden Markov Model (HMM), the system analyzes physical motion to classify four distinct activities: Jumping, Standing, Standstill, and Walking.

## Repository Contents
* `data_HMM/`: Directory containing the 200 harmonized training sequences and 28 unseen testing sequences used for model evaluation.
* `hmm_model.ipynb`: The Jupyter Notebook containing the data pre-processing, feature extraction (time and frequency domains), HMM implementation (using Viterbi and Baum-Welch algorithms), and performance evaluation metrics.
* `Human_Activity_Recognition_Report.pdf`: The final 4-page analytical report detailing the project background, methodology, transition/emission probability heatmaps, and a discussion on model accuracy and sensor noise.

## Dependencies
* `numpy`
* `pandas`
* `scikit-learn`
* `hmmlearn`
* `matplotlib` & `seaborn`