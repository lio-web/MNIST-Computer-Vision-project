# MNIST Computer Vision Project

## Project Overview
This project uses Artificial Neural Networks (ANN) and TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

## Technologies Used
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Tasks
1. Load and explore the MNIST dataset.
2. Visualize sample handwritten digits.
3. Normalize image pixel values.
4. Apply one-hot encoding.
5. Build an ANN using Sequential.
6. Train and validate the model.
7. Visualize training accuracy and loss.
8. Evaluate the model using test data.
9. Generate a confusion matrix and classification report.
10. Save the trained model in Keras format.

## Model Architecture
- Flatten input layer
- Dense layer (128 neurons, ReLU)
- Dropout (0.3)
- Dense layer (64 neurons, ReLU)
- Dropout (0.3)
- Output layer (10 neurons, Softmax)

## Training Configuration
- Optimizer: Adam
- Loss: Categorical Crossentropy
- Epochs: 10
- Batch Size: 128
- Validation Split: 0.1

## Dataset
MNIST handwritten digits dataset.

## Author
Leonard Muhati
