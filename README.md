# DigitNet: A Neural Network Classifier for MNIST — Built Entirely from Scratch with NumPy

Description:

Ever wondered what goes on under the hood of deep learning frameworks? DigitNet is a handcrafted neural network that demystifies the core mechanics of deep learning by building everything from the ground up — no TensorFlow, no PyTorch — just raw NumPy and pure logic.

This project trains a multi-layer neural network on the MNIST handwritten digit dataset, achieving classification through a fully custom pipeline that includes:

🔧 Custom Components

Manual forward propagation with ReLU and softmax

Full backward propagation using the chain rule (yes, by hand!)

Two hidden layers with flexible architecture

Cross-entropy loss and weight updates via gradient descent

📊 Key Features

Clean, vectorized implementation — no for-loops

Input normalization for faster convergence

Debug-friendly modular design

Accuracy evaluation, prediction, and error analysis tools

## Contents
- `notebooks/`: Jupyter Notebook with code and results
- `reports/`: Final report with problem statement, methodology, and results

## 📄 Final Report
See the full report [here](reports/Mathematics_of_NN.pdf).

## 📓 Jupyter Notebook
View the notebook used for this project [here](notebooks/Neural_Network_from_Scratch.ipynb).

## 🧠 Model Used
Only numpy is used to make this

## 🔍 Dataset
The dataset used is the MNIST digits dataset from kaggle, and can be found [here](https://www.kaggle.com/competitions/digit-recognizer/data?select=train.csv)
