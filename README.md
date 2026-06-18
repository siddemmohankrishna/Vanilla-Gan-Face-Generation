# 🎭 Vanilla GAN Face Generation

A Deep Learning project that implements a **Vanilla Generative Adversarial Network (GAN)** using **PyTorch** to generate realistic human face images from random noise vectors. The model is trained to learn the underlying distribution of face images and generate new synthetic faces through adversarial learning.

---

## 🚀 Project Overview

Generative Adversarial Networks (GANs) are a class of deep learning models consisting of two neural networks:

- **Generator** – Generates fake images from random noise.
- **Discriminator** – Classifies images as real or fake.

The Generator tries to fool the Discriminator, while the Discriminator learns to distinguish between real and generated images. Through this competition, the Generator gradually produces realistic-looking images.

---

## ✨ Features

- Vanilla GAN implementation using PyTorch
- Face image generation from random noise
- Adversarial training framework
- Data preprocessing and normalization
- Visualization of generated outputs
- Deep learning model training and evaluation

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Jupyter Notebook

---

## 📂 Dataset

This project uses face image data for training the GAN model.

### Data Preprocessing

- Image resizing
- Tensor conversion
- Pixel normalization
- Batch loading using DataLoader

---

## ⚙️ Model Architecture

### Generator Network

The Generator:

- Accepts random noise vectors as input
- Uses fully connected layers
- Applies Batch Normalization
- Uses ReLU activation functions
- Produces images using Tanh activation

### Discriminator Network

The Discriminator:

- Receives real and generated images
- Uses fully connected layers
- Applies LeakyReLU activation
- Outputs probability scores using Sigmoid activation

---

## 📊 Training Process

1. Load and preprocess image dataset.
2. Generate random noise vectors.
3. Create fake images using the Generator.
4. Train the Discriminator on real and fake images.
5. Train the Generator to fool the Discriminator.
6. Repeat for multiple epochs until convergence.

---

## 📈 Results

The GAN learns meaningful facial features during training and gradually improves its ability to generate realistic human face images from random noise vectors.

Generated images become clearer and more realistic as training progresses.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/siddemmohankrishna/vanilla-gan-face-generation.git
cd vanilla-gan-face-generation
```

Install dependencies:

```bash
pip install torch torchvision numpy matplotlib pillow
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
└── README.md
```

---

## 🎯 Learning Outcomes

- Understanding Generative Adversarial Networks (GANs)
- Adversarial Training Concepts
- Deep Learning with PyTorch
- Image Generation Techniques
- Computer Vision Fundamentals
- Neural Network Optimization

---

## 🔮 Future Improvements

- Deep Convolutional GAN (DCGAN)
- Conditional GAN (CGAN)
- Wasserstein GAN (WGAN)
- Higher Resolution Image Generation
- Model Checkpoint Saving
- Training Loss Visualization

---

## 👨‍💻 Author

**Siddem Mohan Krishna**

🎓 B.Sc Data Science Student  
🤖 Aspiring AI/ML Engineer  
📊 Passionate about Data Science, Deep Learning, and Artificial Intelligence

### Connect with Me

- GitHub: https://github.com/siddemmohankrishna
- Linkedin: https://www.linkedin.com/in/siddem-mohan-krishna-247984378/

---

⭐ If you found this project useful, consider giving it a star on GitHub!
