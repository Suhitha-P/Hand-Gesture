# Hand Gesture Recognition using AlexNet and ResNet


![Hand_Gestures](https://github.com/Suhitha-P/Hand-Gesture/assets/101633121/84500f75-5bc4-4ab8-a46c-d1055af5b27e)



This repository contains an implementation of hand gesture recognition using two popular deep learning architectures: AlexNet and ResNet. Hand gesture recognition is the process of identifying and classifying hand gestures made by a user, which can be utilized in various applications like sign language translation, human-computer interaction, and more.


## Introduction

This project focuses on training and evaluating deep learning models, specifically AlexNet and ResNet, for hand gesture recognition. The goal is to accurately classify hand gestures captured through images using pre-trained models and fine-tuning techniques.

## Prerequisites

- Python 3.x
- TensorFlow and Keras
- NumPy
- Matplotlib

Install the required packages using:

```bash
pip install tensorflow numpy matplotlib
```

## Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/hand-gesture-recognition.git
cd hand-gesture-recognition
```

## Dataset

The dataset used for training and evaluation is not included in this repository. You need to prepare your own dataset containing hand gesture images. Organize the dataset into subfolders where each subfolder corresponds to a specific gesture class. Each image should be named uniquely and have the appropriate file extension (e.g., `.jpg`, `.png`).

Example folder structure:

```
dataset/
|-- class1/
|   |-- gesture1.jpg
|   |-- gesture2.jpg
|   |-- ...
|
|-- class2/
|   |-- gesture1.jpg
|   |-- gesture2.jpg
|   |-- ...
|
|-- ...
```

## Usage

1. Place your dataset in the `dataset` folder following the structure mentioned above.

2. Use the provided Google Colab notebook files to train and evaluate the models:

   - `alexnet.ipynb`: Train and test the AlexNet model.
   - `resnet.ipynb`: Train and test the ResNet model.

3. In Google Colab, run the notebook cells sequentially to train and evaluate the models.

Note: Make sure to adjust any file paths or dependencies if necessary to match your Google Colab environment.
