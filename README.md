# MNIST Digit Classifier – Using ANN (Keras)

This project focuses on classifying handwritten digits from the MNIST dataset using a simple Artificial Neural Network (ANN) built with Keras. It serves as a foundational deep learning exercise and achieves strong results with minimal architecture — making it ideal for understanding the basics of neural networks applied to image classification.


## 📊 About the Dataset

The MNIST dataset is one of the most widely used datasets in computer vision. It consists of **70,000 grayscale images** of handwritten digits (0 through 9), with:

- **60,000 images** for training  
- **10,000 images** for testing  
- Each image is **28x28 pixels**, centered and size-normalized  
- The task is to classify each image into one of **10 classes** (digits 0 to 9)
  

## ✅ Performance

Using a basic feedforward neural network (ANN) without any convolutional layers, the model achieves an impressive **test accuracy of approximately 97.7%** on the MNIST dataset. 

This result shows that even a simple architecture can perform well on structured and clean datasets like MNIST, making it a great entry point for beginners in deep learning.


## 🖼️ Sample Visuals

### Example Digits from MNIST Dataset:
![MNIST Samples](C:\Users\hp\OneDrive\Desktop\digit_classifier\images\sample_predictions.png)

---

### Accuracy Curve During Training:
![Training Accuracy](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/accuracy_plot.png)

> *(Replace image URLs with actual ones from your project repo if needed)*

---

## 📌 Highlights

- Built using **TensorFlow/Keras**
- Clean and minimal ANN achieving **~97.7% accuracy**
- Excellent for beginners exploring deep learning and image classification
- No complex preprocessing or CNNs — just raw pixel values and fully connected layers
