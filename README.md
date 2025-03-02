# Orange vs Tomato Classification

This repository contains a deep learning project for classifying oranges and tomatoes using a neural network. The dataset has been self-collected, and the model is built from scratch using TensorFlow.

## Features
- Self-collected dataset of oranges and tomatoes
- Data preprocessing and augmentation
- Neural network model training from scratch
- Model evaluation and visualization

## Repository Structure
- `data/` - Contains the dataset of oranges and tomatoes.
- `train_model.ipynb` - Notebook for preprocessing data, training, and saving the model.
- `deploy_model.ipynb` - Notebook for loading the model and making predictions.

## Requirements
To run this project, install the following dependencies:

```bash
pip install tensorflow numpy pandas matplotlib opencv-python
```

## Usage
### Training the Model
1. Open `train_model.ipynb` in Jupyter Notebook.
2. Run all cells to preprocess data, train the neural network, and save the model.

### Deploying the Model
1. Open `deploy_model.ipynb` in Jupyter Notebook.
2. Load the trained model and classify new images.

## Dataset
The dataset consists of images of oranges and tomatoes, collected manually.

## Acknowledgments
- **TensorFlow & Keras** for deep learning implementation.
- **OpenCV** for image processing.

Feel free to contribute or raise issues if you have suggestions or improvements!
