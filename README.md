# Ladybug Classification and Spot Counting using Machine Learning

## Overview

This project, developed by Alexis BALAYRE, Augustin CREUSILLET, and Julien GODFROY, is a comprehensive exploration into the realm of machine learning and computer vision. Our goal is to classify two species of ladybugs - _Harmonia axyridis_ and _Coccinella septempunctata_ - and accurately count the spots on their backs. This task is not just academically challenging but also of ecological interest, as _Harmonia axyridis_ is considered invasive in Europe.

## Dataset

We utilise a curated dataset consisting of high-resolution images of the two ladybug species, accompanied by segmentation masks for more precise analysis. Each image in the dataset is labeled with the correct species and the number of spots, which serves as the ground truth for our models.

## Features

- **Data Preparation and Exploration**: Detailed exploration of the dataset, including visualization of the images and segmentation masks to understand the features of each species.
- **Clustering and Visualisation**: Implementing K-means clustering to identify distinct groups within the data based on the features extracted from the images.
- **Classification Model**: Training a RandomForest classifier to distinguish between the two species of ladybugs.
- **Spot Counting**: Utilising region-based properties to count the number of spots on each ladybug, which is crucial for accurate species classification.
- **Deep Learning Approach**: Experimenting with Convolutional Neural Networks (CNNs) to enhance classification accuracy and spot counting.

## Technologies

This project leverages the power of Python and several libraries, including:

- **Pandas & Numpy** for data manipulation,
- **Matplotlib & Seaborn** for data visualisation,
- **Scikit-Learn** for machine learning algorithms and preprocessing,
- **Keras** for building and training deep learning models,
- **Scikit-Image** for image processing tasks.

## Getting Started

To replicate our findings or explore the dataset with your methods, please ensure you have Python 3.6+ installed. Clone this repository, navigate to the project directory, and install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

The main analysis is presented in a Jupyter notebook format. To start exploring, run:

```
jupyter notebook final_project.ipynb
```

Navigate through the notebook to understand the workflow, from data loading and preprocessing to modeling and evaluation.

## License

This project is open-sourced under the MIT license.
