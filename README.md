# Digit-Recognizer-MNIST-
Handwritten Digit Recognition using Convolutional Neural Networks (CNN) and TensorFlow on the MNIST dataset.
# Handwritten Digit Recognition Using CNN

## Project Overview

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from 0 to 9 using the MNIST dataset. CNNs automatically learn image features and achieve high accuracy in image classification tasks.

## Dataset

Dataset: MNIST Handwritten Digit Dataset

* Training Images: 60,000
* Testing Images: 10,000
* Image Size: 28 × 28 pixels
* Classes: 10 (Digits 0–9)

The dataset is loaded directly using TensorFlow/Keras.

## Algorithm Used

Convolutional Neural Network (CNN)

### Architecture

Input Layer (28 × 28 × 1)

↓

Conv2D (32 Filters, ReLU)

↓

MaxPooling2D

↓

Conv2D (64 Filters, ReLU)

↓

MaxPooling2D

↓

Flatten

↓

Dense (128 Neurons, ReLU)

↓

Output Layer (10 Neurons, Softmax)

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib

## Results

* Successfully classified handwritten digits from 0–9.
* Achieved approximately 98–99% test accuracy.
* Demonstrated the effectiveness of CNNs for image classification.

## Applications

* Optical Character Recognition (OCR)
* Bank cheque processing
* Postal code recognition
* Handwritten document digitization

## Conclusion

The CNN model effectively learned image features from handwritten digits and achieved high classification accuracy on the MNIST dataset. This project demonstrates the power of deep learning in image recognition tasks.
