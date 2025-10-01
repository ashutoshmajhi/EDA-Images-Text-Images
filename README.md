This repository contains a Jupyter notebook for an Exploratory Data Analysis (EDA) assignment related to machine learning. The notebook demonstrates fundamental data processing and visualization techniques, including a custom random number generator and data normalization, on a dataset that appears to be related to EEG (Electroencephalography) signals.

Key Features
Custom Random Number Generator: A custom function is implemented to generate a list of random numbers. This function is then used to create a 1D plot and an N x N array visualization.

Data Loading and Exploration: The notebook demonstrates how to explore a dataset stored in a mounted Google Drive folder. It reads and processes metadata to select specific data samples.

Data Sampling and Analysis: Using the custom random number generator, the notebook selects 12 random EEG data samples and prints their metadata.

Data Normalization: A custom function is provided to normalize data within a specified range [-x, x].

Data Visualization: The notebook includes examples of plotting both 1D and 2D data, as well as normalizing and plotting four randomly selected EEG signals.

Dependencies
This project requires the following Python libraries:

matplotlib.pyplot: For plotting and data visualization.

pandas: For data manipulation and analysis, primarily for working with DataFrames.

numpy: For numerical operations and array handling.

os: For interacting with the operating system, such as managing file paths.

IPython.display: For displaying rich output like images and plots within the notebook.

time: Used to seed the random number generator.
