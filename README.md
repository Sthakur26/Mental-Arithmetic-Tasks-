EEG Data Analysis for Cognitive State Classification
Overview
This project involves the analysis of EEG data to classify different cognitive states using advanced deep learning techniques. The data is sourced from the Mental Arithmetic Tasks Dataset available at PhysioNet (https://physionet.org/content/eegmat/1.0.0/).

Objectives
The objectives of this project are:

Load the EEG data
Perform Power Spectral Density (PSD) analysis to calculate the band-wise PSD for both rest and task states
Implement and evaluate multiple deep learning models for binary classification using the Python library MNE
Steps to Achieve
1. Load the EEG data
Download the EEG data ZIP file from PhysioNet (https://physionet.org/content/eegmat/1.0.0/)
Extract the ZIP file to a directory of your choice
Load the EEG data file using the mne library
2. Power Spectral Density (PSD) Analysis
Calculate the band-wise PSD for both rest and task states using the mne library
Focus on the following frequency bands: Delta (1-4 Hz), Theta (4-8 Hz), Alpha (8-12 Hz), Beta (12-30 Hz), and Gamma (30-100 Hz)
Compare the PSDs of the two states and summarize your findings
3. Deep Learning Classification
Extract relevant features from the cleaned data
Implement binary classification using at least two different deep learning models (e.g., EEGNet, TSCeption, ViT, ATCNet, VAE)
Train and validate the model using the provided dataset
Evaluate the models using appropriate metrics (accuracy, precision, recall, F1-score) and discuss the results
Submission Guidelines
Ensure that your Jupyter Notebook is well-organized and thoroughly commented
Share your completed notebook by submitting the GitHub repository link
Dataset
The dataset used in this project is the Mental Arithmetic Tasks Dataset available at PhysioNet (https://physionet.org/content/eegmat/1.0.0/).
Initial release (1.0.0)

