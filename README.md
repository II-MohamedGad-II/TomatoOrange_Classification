Orange vs Tomato Classification using Neural Networks
This repository contains a deep learning project for classifying oranges and tomatoes using a neural network. The dataset has been collected manually and is used to train a model from scratch.

🚀 Features
Custom dataset of oranges and tomatoes
Preprocessing of images for deep learning
Training a neural network for classification
Model evaluation and accuracy assessment
📂 Repository Structure
data/ - Contains the manually collected images of oranges and tomatoes
preprocessing.py - Script for image preprocessing (resizing, normalization, augmentation)
train_model.py - Code for training the neural network
evaluate_model.py - Model testing and performance evaluation
saved_model/ - Directory for storing the trained model
🛠 Requirements
Install the required dependencies before running the project:

bash
نسخ
تحرير
pip install tensorflow keras numpy pandas matplotlib opencv-python
📌 Usage
1️⃣ Data Preprocessing
Run the preprocessing script to prepare the dataset:

bash
نسخ
تحرير
python preprocessing.py
2️⃣ Model Training
Train the neural network using:

bash
نسخ
تحرير
python train_model.py
3️⃣ Model Evaluation
Evaluate the trained model with test data:

bash
نسخ
تحرير
python evaluate_model.py
📊 Dataset
The dataset consists of self-collected images of oranges and tomatoes. Images have been processed and labeled for training purposes.


🤝 Contributing
Feel free to open issues or contribute to improve the model.

🏆 Acknowledgments
Thanks to TensorFlow/Keras for deep learning tools and OpenCV for image processing.
