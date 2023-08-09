# Digit Classification Neural Network

This project focuses on building a handwritten digit classifier using the MNIST dataset. The goal is to create a model capable of correctly identifying the digits (0-9) present in grayscale images.

## Features and Usage

- `Import Libraries:` The code imports necessary libraries for data handling, visualization, and model building.

- `Load and Prepare Data:` The MNIST dataset is loaded and prepared for training and testing.

- `Visualize Data:` Sample images are displayed, and the distribution of classes is visualized.

- `Normalization:` Data normalization enhances training by scaling pixel values.

- `One-Hot Encoding:` Labels are converted into one-hot encoded vectors for effective model training.

- `Build Model:` A neural network model is defined with layers for processing.

- `Train Model:` The model is trained using the training dataset, and loss and accuracy are tracked.

- `Analyze Performance:` Training and validation loss and accuracy are plotted for analysis.

- `Evaluate Model:` Model performance is evaluated on both training and testing datasets.

## Dependencies

- matplotlib
- numpy
- tensorflow
- colorama
- scikit-learn

For installing dependencies, run:
```bash
pip install -r requirements.txt
```