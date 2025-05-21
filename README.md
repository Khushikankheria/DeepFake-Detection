
# 🧠 Fact or Fiction: Unveiling Deepfakes with Machine Learning

DeepFakes are AI-generated synthetic media where a person’s likeness is replaced or altered in a highly realistic manner. These can be misused for identity theft, misinformation, and security breaches. This project focuses on detecting DeepFakes using **MesoNet**, a neural network architecture specifically designed for this task.

We also address the challenge of detecting DeepFakes in low-quality, compressed videos by introducing a preprocessing module that enhances detection robustness.

---

## 🧾 Features

- DeepFake detection using MesoNet
- Resilience to compressed and low-resolution videos
- Visualization of prediction confidence scores
- Tested on multiple datasets: custom dataset and **FaceForensics (Face2Face)**

---

## 🧰 Tech Stack

- Python 3.5
- Keras 2.1.5
- TensorFlow 
- OpenCV, NumPy, Matplotlib
- Jupyter Notebook (for analysis and visualization)

---

## 📊 Datasets Used

- **Custom DeepFake Dataset**: Augmented real vs. synthetic images from various internet sources.
- **FaceForensics (Face2Face)**: Benchmark dataset for facial reenactment detection.

All datasets were standardized to ensure balance in resolution and diversity.

---

## ⚙️ Implementation

- Images resized to `256x256x3`
- Batch training with data augmentation (zoom, rotation, brightness, hue shifts)
- MesoNet model used with preprocessing module for enhanced feature extraction
- Output: Probability of image being a DeepFake, with model confidence visualization

---

## 📈 Results

- High prediction accuracy on both custom and Face2Face datasets
- Robust performance against compressed input
- Visual confidence scores confirmed model's reliability

