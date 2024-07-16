# Skin Lesion Classification

This repository contains code for classifying skin lesion images using machine learning algorithms. The goal of this project is to develop models that can accurately classify skin lesions into different categories based on images.

## Dataset

The dataset used in this project is the HAM10000 dataset from Kaggle 'https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000' , which consists of 10,000 dermatoscopic images of common pigmented skin lesions. Each image is accompanied by metadata including lesion type, patient information, and image quality ratings.

Original Data Source: https://challenge2018.isic-archive.com

## Code Overview

- UsingMLModels_.ipynb, UsingCNNModel .ipynb: Jupyter Notebook containing the Python code for data preprocessing, model training, and evaluation.
- HAM10000_metadata.csv: CSV file containing metadata for the images.
- HAM10000_images_part1, HAM10000_images_part2: Directory containing the skin lesion images.(since it is a very large dataset, it is not been added to the repository) 
- hmnist_28_28_L.csv: Pixel data for skin lesion images in grayscale (28x28 pixels).
- hmnist_28_28_RGB.csv: Pixel data for skin lesion images in RGB color (28x28 pixels).
- hmnist_8_8_L.csv: Pixel data for skin lesion images in grayscale at a reduced resolution (8x8 pixels).
- hmnist_8_8_RGB.csv: Pixel data for skin lesion images in RGB color at a reduced resolution (8x8 pixels).

## Dependencies

1. Python 3.x
2. Libraries:

- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- imbalanced-learn
- OpenCV
- TensorFlow/Keras 

## Usage

1. Create the repository
2. Install the dependencies
3. Run the Jupyter Notebook skin_lesion_classification.ipynb to execute the code step by step.
4. Follow the instructions provided in the notebook to load the dataset, preprocess the images, train machine learning models (e.g., K-Nearest Neighbors, Support Vector Machine, Random Forest), and evaluate their performance.

## Results

The trained models are evaluated using accuracy score, confusion matrix, and classification report. The performance metrics provide insights into the effectiveness of each model in classifying skin lesions.In ML models ,'Support Vector Machine' gave highest accuracy of 91.5%. In DL models 'Convolutional Neural Network' gave accuracy of 94%.

## Conclusion

While traditional models showed promising results, the CNN model exceeded them by obtaining an amazing 94% accuracy. These findings highlight the potential of machine learning, particularly CNNs, to help dermatologists accurately diagnose skin lesions.
