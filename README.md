# CIFAR-10 Image Classification with CNN and Data Augmentation

This repository contains Python scripts for image classification using Convolutional Neural Networks (CNN) on the CIFAR-10 dataset. Additionally, it includes data augmentation techniques using TensorFlow's ImageDataGenerator to enhance the model's robustness.

## **Files**
### **File 1 - CIFAR10_CNN_Training.ipynb**
- This Jupyter Notebook file focuses on:
- Loading and visualizing the CIFAR-10 dataset
- Data preparation including normalization and categorical conversion
- Building a CNN model using TensorFlow/Keras
- Training the CNN model on the CIFAR-10 dataset
- Evaluating the model's performance on the test dataset
- Visualizing predictions and creating a confusion matrix
- Saving the trained model

### **File 2 - Image_Augmentation.ipynb**
This notebook covers:

- Loading CIFAR-10 dataset
- Implementing data augmentation using ImageDataGenerator in Keras
- Displaying augmented images for training

## **Usage**
1. Clone the repository to your local environment:
   ```
   git clone https://github.com/your-username/CIFAR-10-Image-Classification.git
   ```
2. Open and run the Jupyter Notebooks (.ipynb) in your preferred environment (Jupyter Notebook, Google Colab, etc.).
3. File 1 (CIFAR10_CNN_Training.ipynb) demonstrates the CNN model training process on the CIFAR-10 dataset and provides insights into its performance.
4. File 2 (Image_Augmentation.ipynb) showcases data augmentation techniques using TensorFlow's ImageDataGenerator, providing visual examples of augmented images.

## **Requirements**
- Python 3
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- PIL (Python Imaging Library)

## **Note**
- The code assumes basic familiarity with TensorFlow/Keras, CNNs, and image classification concepts.
- Adjust hyperparameters, model architecture, or augmentation techniques for experimentation and improved performance.