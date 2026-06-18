# 🎭 Vanilla GAN Face Generation

A Deep Learning project that implements a **Vanilla Generative Adversarial Network (GAN)** using **PyTorch** to generate realistic human face images from random noise vectors. The model is trained on the CelebA dataset and learns to create synthetic face images through adversarial training.

## 🚀 Project Overview

Generative Adversarial Networks (GANs) are a powerful class of deep learning models consisting of two competing neural networks:

- **Generator** – Generates fake face images from random noise.
- **Discriminator** – Distinguishes between real and generated images.

The Generator continuously improves its ability to create realistic images, while the Discriminator learns to identify fake images. Through this adversarial process, the model learns the underlying distribution of facial features and generates realistic faces.

---

## ✨ Features

- Vanilla GAN implementation using PyTorch
- Face image generation from random noise vectors
- Adversarial training framework
- Image preprocessing and normalization
- Training visualization and monitoring
- Deep learning model development using Jupyter Notebook

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pillow (PIL)
- Jupyter Notebook

---

## 📂 Dataset

This project uses the **CelebFaces Attributes Dataset (CelebA)** for training.

### Dataset Source

- Official Website: https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

### Dataset Information

- Over 200,000 celebrity face images
- Large-scale face attributes dataset
- Widely used for computer vision and generative modeling research
- High-quality aligned face images

### Preprocessing Steps

- Image resizing
- Tensor conversion
- Pixel normalization
- Batch loading using PyTorch DataLoader

---

## ⚙️ Model Architecture

### Generator Network

The Generator:

- Takes a random noise vector as input
- Uses fully connected neural network layers
- Applies Batch Normalization
- Uses ReLU activation functions
- Produces images using Tanh activation

### Discriminator Network

The Discriminator:

- Receives real and generated images
- Uses fully connected neural network layers
- Applies LeakyReLU activation
- Outputs a probability score using Sigmoid activation

---

## 📊 Methodology

### Step 1: Data Preparation

- Download the CelebA dataset
- Preprocess and normalize images
- Create batches using DataLoader

### Step 2: Generator Training

- Generate random noise vectors
- Produce fake face images
- Attempt to fool the Discriminator

### Step 3: Discriminator Training

- Train on real images from CelebA
- Train on fake images from the Generator
- Learn to classify images correctly

### Step 4: Adversarial Learning

- Alternate training between Generator and Discriminator
- Minimize Generator loss
- Maximize Discriminator accuracy

### Step 5: Face Generation

- Generate realistic face images from unseen random noise vectors

---

## 📈 Results

The GAN successfully learns meaningful facial features from the CelebA dataset and generates synthetic human faces from random noise vectors.

As training progresses:

- Generated images become sharper
- Facial structures become more realistic
- Image quality improves through adversarial learning

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/siddemmohankrishna/vanilla-gan-face-generation.git
cd vanilla-gan-face-generation
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
vanilla_gan.ipynb
```

---

## 📁 Project Structure

```text
vanilla-gan-face-generation/
│
├── vanilla_gan.ipynb
├── requirements.txt
└── README.md
```

---

## 🎯 Learning Outcomes

- Understanding GAN Architecture
- Adversarial Training Techniques
- Deep Learning with PyTorch
- Face Image Generation
- Neural Network Optimization
- Computer Vision Fundamentals

---

## 🔮 Future Improvements

- Deep Convolutional GAN (DCGAN)
- Conditional GAN (CGAN)
- Wasserstein GAN (WGAN)
- Higher Resolution Face Generation
- Model Checkpoint Saving
- Training Loss Visualization Dashboard

---

## 🙏 Acknowledgements

- CelebA Dataset by The Chinese University of Hong Kong (CUHK)
- PyTorch Deep Learning Framework
- Open Source AI Research Community

---

## 👨‍💻 Author

**Siddem Mohan Krishna**

🎓 B.Sc Data Science Student  
🤖 Aspiring AI/ML Engineer  
📊 Passionate about Artificial Intelligence, Deep Learning, and Data Science

### GitHub

- Github: https://github.com/siddemmohankrishna
- Linkedin: https://www.linkedin.com/in/siddem-mohan-krishna-247984378/

---

⭐ If you found this project useful, consider giving it a star on GitHub!

---

⭐ If you found this project useful, please consider giving it a star!
