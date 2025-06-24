# My First Neural Network

This project demonstrates a simple neural network built using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

## 📌 Project Overview

- 📚 Dataset: MNIST (70,000 grayscale images of handwritten digits)
- 🧠 Model: Fully connected neural network
- 🛠 Tools: Python, TensorFlow, Keras
- 🧪 Task: Multi-class classification (digits 0–9)

## 🚀 How to Run

1. Install dependencies:
    ```bash
    pip install tensorflow
    ```

2. Run the notebook:
    - Using Jupyter:
        ```bash
        jupyter notebook my_first_neural_network_fixed.ipynb
        ```
    - Or open directly in VS Code.

## 📈 Model Architecture

- Input Layer: Flatten 28x28 images into 784-dim vector
- Hidden Layer: Dense layer with 128 units, ReLU activation
- Output Layer: Dense layer with 10 units (digits 0-9), outputs logits

## 🖼 Output

After training for 5 epochs, the model achieves ~97-98% accuracy on the test dataset.

## 📁 Files Included

- `my_first_neural_network_fixed.ipynb` – main notebook
- `README.md` – project documentation

## 🧑‍💻 Author

Jayaprakash M  
Feel free to fork or star this repo and try experimenting with other datasets or model architectures!
