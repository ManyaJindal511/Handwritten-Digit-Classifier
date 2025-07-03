# 🧠 MNIST Digit Classification with Keras

This project trains a neural network on the **MNIST handwritten digit dataset** using **TensorFlow/Keras**. It uses the `sparse_categorical_crossentropy` loss function, which is perfect for integer-labeled multiclass classification tasks.

## 🗂️ Dataset

- **Dataset**: [MNIST](http://yann.lecun.com/exdb/mnist/)
- **Classes**: 10 (digits 0–9)
- **Image Size**: 28x28 grayscale

Keras provides MNIST out of the box:

```python
from tensorflow.keras.datasets import mnist
(X_train, y_train), (X_test, y_test) = mnist.load_data()
