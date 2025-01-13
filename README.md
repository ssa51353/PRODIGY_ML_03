# SVM for Cat vs Dog Classification

This project demonstrates the use of a Convolutional Neural Network (CNN) with a Support Vector Machine (SVM) loss function (`hinge`) for classifying images of cats and dogs. The dataset used is the popular "Dogs vs Cats" dataset available on Kaggle.

## Features
- Data loading and preprocessing using TensorFlow's image dataset utilities.
- CNN architecture with multiple convolutional and pooling layers.
- Use of the hinge loss function for binary classification.
- Real-time GPU memory management for optimal training performance.
- Model saving for future use and deployment.

## Dataset
The dataset is sourced from Kaggle: [Dogs vs Cats Dataset](https://www.kaggle.com/salader/dogs-vs-cats).

### Directory Structure
- `/content/train/`: Training images.
- `/content/test/`: Testing images.

## Installation

### Prerequisites
- Python 3.7 or higher
- Kaggle API setup for downloading datasets
- GPU support for TensorFlow (optional but recommended)

### Requirements
Install the required Python libraries using the following command:

```bash
pip install -r requirements.txt
