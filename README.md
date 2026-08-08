# 🧠 Neural Network From Scratch

A simple feedforward neural network implemented **from scratch using Python and NumPy**, without using high-level deep learning frameworks such as TensorFlow or PyTorch.

The project demonstrates the fundamental concepts behind how a neural network learns, including forward propagation, loss calculation, backpropagation, and gradient descent.

## 🎯 Project Objective

The main objective of this project is to understand the internal working of a neural network by implementing the core learning process manually rather than relying on pre-built deep learning frameworks.

The network is trained to solve the classic **XOR classification problem**.

## 🧠 Neural Network Architecture

```text
Input Layer
    ↓
Hidden Layer
    ↓
Output Layer

2 Input Neurons
       ↓
4 Hidden Neurons
       ↓
1 Output Neuron
```

### Learning Process

```text
Input Data
    ↓
Forward Propagation
    ↓
Prediction
    ↓
Loss Calculation
    ↓
Backpropagation
    ↓
Gradient Descent
    ↓
Weight Update
    ↓
Repeat
```

## 🚀 Features

* Forward propagation
* Backpropagation
* Gradient descent
* ReLU activation function
* Sigmoid activation function
* Binary cross-entropy loss
* Weight and bias optimization
* XOR classification
* Training loss visualization
* Prediction system
* Accuracy calculation

## 🛠️ Technologies Used

* Python
* NumPy
* Matplotlib
* Google Colab

## 📊 Dataset

This project uses the classic XOR dataset.

| Input    | Expected Output |
| -------- | --------------: |
| `[0, 0]` |               0 |
| `[0, 1]` |               1 |
| `[1, 0]` |               1 |
| `[1, 1]` |               0 |

The XOR problem is useful for demonstrating neural networks because the data is **not linearly separable**.

## 📈 Results

After training, the neural network successfully learns the XOR relationship.

Example:

```text
Input       Prediction
----------------------
[0, 0]      0
[0, 1]      1
[1, 0]      1
[1, 1]      0
```

The training process can also be visualized using the loss curve to observe how the model improves over time.

## 🔬 Concepts Demonstrated

This project helped explore the fundamentals of:

* Neural network architecture
* Weights and biases
* Activation functions
* Forward propagation
* Loss functions
* Gradients
* Backpropagation
* Gradient descent
* Model training
* Binary classification

## ▶️ How to Run

### Google Colab

Open the notebook:

`Neural-Network-From-Scratch.ipynb`

and run the cells sequentially.

### Local Setup

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/neural-network-from-scratch.git
```

Navigate into the project:

```bash
cd neural-network-from-scratch
```

Install dependencies:

```bash
pip install numpy matplotlib
```

Run the notebook using Jupyter or open it in VS Code.


⭐ If you found this project useful, feel free to explore the repository and follow the upcoming AI/ML projects.
