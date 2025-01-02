# Custom-MLP-Model-for-Flower-Classification
<p>The provided program implements a Custom MultiLayer Perceptron (MLP) model for classifying flower images into five categories. The program utilizes TensorFlow and Keras, showcasing the process of data augmentation, custom layer creation, model training, and evaluation using a custom training loop.</p>

## Key Features
Data Augmentation: Applies transformations like rotation, zoom, and flips to increase training data diversity.

### Custom Layers:
MyFlatten: Custom implementation of a flatten layer.
MyDense: Custom implementation of a dense (fully connected) layer with activation functions.
Custom Loss: Implements categorical cross-entropy loss manually for flexibility.
Custom Training Loop: Manages forward passes, loss computation, gradient updates, and metric tracking explicitly.

### Model Architecture:
Input layer followed by custom flatten and dense layers.
Fully connected layers with ReLU and Softmax activations for classification.
### Training and Evaluation:
Uses ImageDataGenerator for data preprocessing.
Tracks loss and accuracy during training and validation.

## Install the Package
pip install tensorflow matplotlib
<p>in the terminal of a Python environment</p> <p>Ensure you have TensorFlow and Matplotlib installed before running the program. For TensorFlow installation instructions, visit [TensorFlow Installation](https://www.tensorflow.org/install).</p>

### Running the Program
Dataset Preparation
Extract the flower dataset from the zip file to the appropriate directory.
Structure the dataset into training and validation directories.
#### On Google Colab
Mount Google Drive and set paths to the dataset accordingly.
Use the provided script to unzip and organize the dataset.
#### On Local Machine
Ensure the dataset path is correctly set in the script for training and validation directories.
Use the provided script to unzip the dataset.

## Contributor
<p>Lawrence Menegus</p>
