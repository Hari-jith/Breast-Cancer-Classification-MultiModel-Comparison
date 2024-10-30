# Breast-Cancer-Classification-MultiModel-Comparison
A comprehensive breast cancer classification project that leverages multiple pre-trained models (VGG19, DenseNet121, EfficientNetB0, InceptionV3) for accurate categorization of benign and malignant histopathology images from the BreaKHis dataset.
# Breast Cancer Classification Using Multi-Model Deep Learning

This project is a breast cancer classification system that employs multiple deep learning architectures, including VGG19, DenseNet121, EfficientNetB0, and InceptionV3, to classify histopathology images as benign or malignant. Each model is trained and evaluated independently, providing a comparative analysis of their performance on this specific task. This system is designed to aid in medical diagnosis by accurately identifying the nature of breast tumors.

## Dataset
The model uses the **BreaKHis** dataset, which includes breast cancer histopathology images categorized into benign and malignant classes. The dataset covers images at various magnification levels. To use this dataset, download it from [Kaggle](https://www.kaggle.com/anaselmasry/breast-cancer-dataset) and ensure it is organized in a specified structure.

Dataset Link : https://www.kaggle.com/anaselmasry/breast-cancer-dataset


![Dataset_samp](https://github.com/user-attachments/assets/914de685-2430-4008-a0aa-8b21f79dde0b)


## Project Structure
The project follows a structured pipeline:
1. **Data Download and Organization**: Downloads the dataset using Kaggle API and organizes it into the appropriate directory.
2. **Data Preprocessing**: Resizes images to a uniform size, normalizes them, and balances the classes to prevent bias in training.
3. **Model Training**: Four pre-trained models (VGG19, DenseNet121, EfficientNetB0, and InceptionV3) are fine-tuned to classify the images.
4. **Evaluation**: Evaluates each model on the test dataset, displaying accuracy, confusion matrix, and classification report.
5. **Sample Testing**: Includes a function to test individual sample images, showing predictions with probability scores for benign or malignant classification.

## Requirements
- Python 3.x
- TensorFlow and Keras
- OpenCV
- Kaggle API
- Scikit-learn
- Matplotlib
- Seaborn

Models Implemented
VGG19
EfficientNetB0
DenseNet121
InceptionV3
Each model architecture has been fine-tuned with a custom classification head to output benign or malignant predictions.


Model Evaluation
The models are evaluated on a balanced test set to prevent skewed accuracy metrics. Evaluation metrics include:

Accuracy
Confusion Matrix
Classification Report







## Contact


**Email**: harijithmm8122003@gmail.com
