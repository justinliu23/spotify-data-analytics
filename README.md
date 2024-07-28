# spotify-data-analytics

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Results](#results)

## Features
This project explores machine learning techniques and visualizations to analyze music trends on Spotify. It includes:
- Data preprocessing and exploration using pandas and matplotlib.
- Advanced statistical analysis such as Pearson correlation to discover relationships between features.
- Implementation of PCA and t-SNE for dimensionality reduction and visualization.
- Utilization of permutation importance to identify key features impacting song popularity.

## Installation
Ensure the following Python packages are installed to run the notebook:
```
pip install pandas numpy matplotlib scikit-learn
```
Clone the repository and navigate to the directory containing the notebook.

## Usage
The Jupyter Notebook is structured to guide you through loading the data, performing exploratory data analysis, applying machine learning algorithms, and visualizing the results. Execute the notebook cells in sequence to replicate the analysis.

## Configuration
No additional configuration is necessary; however, adjustments can be made to the parameters of the machine learning models to explore different aspects of the data.

## Model Architecture
The project applies several machine learning models, including PCA and t-SNE, to reduce the high-dimensional data into a more interpretable form. This approach helps in visualizing complex datasets and making insightful conclusions.

## Dataset
The dataset comprises data on Spotify tracks, including various attributes like danceability, energy, key, and the number of streams. Detailed exploration and preprocessing steps are provided to handle missing and non-numeric values.

## Results
The analysis results in a detailed understanding of the factors that contribute to a song's popularity on streaming platforms. Visualizations and statistical tests illustrate the relationships between different attributes and streaming numbers.
