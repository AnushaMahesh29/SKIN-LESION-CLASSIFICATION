# Skin Lesion Classification

This repository contains code for classifying skin lesion images using machine learning algorithms. The goal of this project is to develop models that can accurately classify skin lesions into different categories based on images.

## Dataset

The dataset used in this project is the HAM10000 dataset from Kaggle 'https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000' , which consists of 10,000 dermatoscopic images of common pigmented skin lesions. Each image is accompanied by metadata including lesion type, patient information, and image quality ratings.

Original Data Source: https://challenge2018.isic-archive.com

## Code Overview

- skin_lesion_classification.ipynb: Jupyter Notebook containing the Python code for data preprocessing, model training, and evaluation.
- HAM10000_metadata.csv: CSV file containing metadata for the images.
- HAM10000_images/: Directory containing the skin lesion images.

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
- TensorFlow/Keras (if using deep learning models)

## Usage

1. Clone the repository:
2. Install the dependencies
3. Run the Jupyter Notebook skin_lesion_classification.ipynb to execute the code step by step.
4. Follow the instructions provided in the notebook to load the dataset, preprocess the images, train machine learning models (e.g., K-Nearest Neighbors, Support Vector Machine, Random Forest), and evaluate their performance.

## Results

The trained models are evaluated using accuracy score, confusion matrix, and classification report. The performance metrics provide insights into the effectiveness of each model in classifying skin lesions.'Support Vector Machine' gave highest accuracy of 91.5%.

## Conclusion

In this project, we explored different traditional machine learning models for skin lesion classification and evaluated their performance using the HAM10000 dataset. The results demonstrate the potential of machine learning in assisting dermatologists in diagnosing skin lesions.
