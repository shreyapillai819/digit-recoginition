# Digit Recognizer

This project implements a digit recognition system using the MNIST dataset. It combines both the training of the model and a GUI interface for testing the trained model.

---

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)

---

## Project Description
This project involves:
1. Training a Convolutional Neural Network (CNN) to classify handwritten digits (0-9) using the MNIST dataset.
2. Providing a Graphical User Interface (GUI) for testing the trained model by drawing digits.

The trained model achieves high accuracy on the MNIST test dataset, and the GUI adds an interactive layer to test its real-time predictions.

---

## Features
- **Model Training**: CNN-based model training for digit recognition.
- **Interactive GUI**: A canvas to draw digits and get predictions.
- **Model Persistence**: Save the trained model (`mnist.h5`) for future use.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: TensorFlow/Keras, Tkinter
- **Dataset**: MNIST

---

## Usage

### Train the Model
1. Use the `train_digit_recognizer.py` script to train the model.
   - It preprocesses the MNIST dataset and trains a CNN.
   - The trained model is saved as `mnist.h5`.

   Run:
   ```bash
   python train_digit_recognizer.py

2.GUI
 Run:
   ```bash
python gui_digit_recognizer.py

