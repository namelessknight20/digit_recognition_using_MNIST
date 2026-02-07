Handwritten Digit Recognizer (PyTorch)
A beginner-friendly Convolutional Neural Network (CNN) built with PyTorch to recognize handwritten digits using the MNIST dataset. This project demonstrates the full machine learning pipeline: from data preprocessing and model architecture design to real-world testing with custom JPEG images.

🚀 Features
Pure PyTorch Implementation: No TensorFlow/Keras used, focusing on the torch ecosystem.

CNN Architecture: Includes Convolutional layers, Max-Pooling, and Dropout for high accuracy.

Custom Image Testing: A built-in utility to test your own handwriting (JPEG/PNG) using PIL preprocessing.

High Performance: Achieves 98%+ accuracy on the MNIST test set in just a few epochs.

🛠️ Tech Stack
Language: Python

Core Library: torch

Computer Vision: torchvision (for data) and Pillow (for custom image processing)

Visualization: matplotlib

📋 How It Works
Data Loading: Downloads the MNIST dataset via torchvision.datasets.

Preprocessing: Normalizes grayscale images and converts them to 28x28 tensors.

Model Training: Uses the Adam optimizer and CrossEntropyLoss to train the CNN.

Inference: Processes custom images by inverting colors (black background, white ink) and resizing to match the MNIST training style.

🔧 Installation & Usage
Clone the repository:

Bash
git clone https://github.com/your-username/digit_recognition_using_MNIST.git
Install dependencies:

Bash
pip install torch torchvision pillow matplotlib
Run the notebook/script: Execute the training loop and then use the predict_my_digit function to test your own images.

📊 Results
The model typically reaches:

Training Loss: ~0.02

Test Accuracy: 99%
