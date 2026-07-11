# Plant Disease Prediction Using CNN

## Overview
This project is a deep learning-based image classification system that detects plant diseases from leaf images using a Convolutional Neural Network (CNN).

The model analyzes leaf images and classifies them into different disease categories, helping in the early identification of plant diseases.

## Technologies Used
- Python
- TensorFlow / Keras
- Convolutional Neural Network (CNN)
- NumPy
- Pandas
- Matplotlib
- OpenCV

## Dataset
The model is trained using the **PlantVillage** dataset, which contains images of healthy and diseased plant leaves from multiple crop species.

**Dataset Source:**  
https://www.kaggle.com/datasets/mohitsingh1804/plantvillage

The original dataset contains approximately **54,000+ images** across **38 plant disease classes**. For model training and experimentation, a subset of the dataset was used while preserving the original class-wise folder structure.

## Project Workflow

1. Data Collection
2. Image Preprocessing
3. Data Augmentation
4. CNN Model Training
5. Model Evaluation
6. Disease Prediction

## Model Architecture

The CNN model consists of:
- Convolutional layers for feature extraction
- Max Pooling layers for dimensionality reduction
- Fully Connected (Dense) layers for classification
- Softmax activation for multi-class prediction

## Results

The trained CNN model can classify plant leaf images into different disease categories, enabling accurate plant disease prediction.

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Download the PlantVillage dataset from the link above.
4. Update the dataset path in the notebook (if required).
5. Run the Jupyter Notebook to train the model or make predictions.

## Author

**KR Rohith**
