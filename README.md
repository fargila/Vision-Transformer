# 🧠 Vision Transformer (ViT) - Image Classification with PyTorch

This project implements a **Vision Transformer (ViT)** model from scratch using PyTorch. Inspired by the transformer architecture originally designed for natural language processing, ViT applies self-attention mechanisms to image patches, offering a powerful alternative to traditional convolutional neural networks (CNNs).

---

## 📸 What Is a Vision Transformer?

Instead of processing entire images with convolutions, Vision Transformers:
- Divide images into fixed-size patches
- Flatten and embed each patch into a vector
- Add positional encodings to retain spatial context
- Pass the sequence of patch embeddings through transformer encoder blocks
- Use a classification token (`[CLS]`) to predict image labels

---

## 🚀 Features

- Patch embedding layer
- Multi-head self-attention
- Positional encoding
- Transformer encoder blocks
- Classification head
- Optional training loop for datasets like CIFAR-10 or MNIST

---

## 🛠️ Installation & Setup

To run this project locally, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/fargila/Vision-Transformer.git
cd Vision-Transformer
```

### 2. Set Up Your Environment

Make sure you have Python 3.7+ and install the required packages:
```bash
pip install torch torchvision matplotlib numpy
```

### 3. Run the Notebook

You can run the notebook using Jupyter or Google Colab:
```bash
jupyter notebook Vision_Transformer.ipynb
```
Or open it directly in [Google Colab](https://colab.research.google.com/) for a cloud-based experience.

---

## 📊 DataSet

You can modify the notebook to use datasets like:
- [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- [MNIST](https://yann.lecun.com/exdb/mnist/)

These are available via torchvsion.datasets

---

## 🙌 Showing Gratitude

This project was created with the help of [FreeCodeCamp.org](https://www.freecodecamp.org/), whose tutorials and resources are made free for anyone interested in coding. This link goes to their website, but you can also find them on Youtube at [Their Channel](https://www.youtube.com/@freecodecamp).
