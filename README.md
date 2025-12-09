# 🧠 Classification using Artificial Neural Network (ANN)

## 📘 Overview
This project demonstrates **image classification** using an **Artificial Neural Network (ANN)** built with **TensorFlow** and **Keras**.  
The dataset was imported directly from `keras.datasets`. The goal was to understand how neural networks learn and to observe the difference in training speed between CPU and GPU execution.

---

## 🚀 Project Highlights
- Implemented a basic **ANN model** for image classification.  
- Used **TensorFlow/Keras** for building, training, and evaluating the model.  
- Learned how model training speed varies between **CPU** and **GPU**.  
- Observed that deep learning models train **significantly faster on GPUs** compared to CPUs.

---

## 🧩 Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, Matplotlib  
- **Dataset:** Imported from `keras.datasets` (e.g., MNIST or CIFAR-10)

---

## ⚙️ Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/image-classification-ann.git
   cd image-classification-ann

   🖥️ Performance Note

Training the model on a CPU (Intel integrated graphics) was slow, demonstrating how much time deep learning models require without GPU acceleration.

💡 Pro Tip:
For deep learning projects, prefer a laptop or system with an NVIDIA GPU that supports CUDA and cuDNN. It makes model training 10–50× faster.

Results

Model successfully classified images from the dataset.
Achieved reasonable accuracy after several epochs.
Observed significant performance improvement potential with GPU usage.
