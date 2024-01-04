# Comparative Analysis of Neural Networks for COVID Mask Classification

## CovidMask-NeuralNetwork-Analysis

This Jupyter notebook, authored by Md Wahid Hassan, is focused on developing and evaluating different neural network architectures for image classification using the COVID Mask Dataset.

## Description
### NN Assignment - Task 3: Neural Network Development for COVID Mask Classification

Authored by Md Wahid Hassan, this Jupyter notebook is an in-depth exploration of building and training various neural network models using the COVID Mask Dataset. It demonstrates a comprehensive approach to implementing and evaluating neural networks in PyTorch.

#### Key Components:

1. **COVIDMaskDataset Class**:
   - A custom PyTorch [Dataset](https://www.dropbox.com/scl/fi/12ref0i4elyyzy7dgnh24/COVID_Mask.zip?rlkey=anp2khrq34kmz22iw1j89vh8f&dl=0) class designed to handle the COVID Mask Dataset. It loads images and labels from specified file paths.

2. **Neural Network Models**:
   - `bFCNN`: Basic Fully Connected Neural Network with a single hidden layer.
   - `iFCNN`: Improved Fully Connected Neural Network featuring four hidden layers and dropout for regularization.
   - `bCNN`: Basic Convolutional Neural Network comprising a convolutional layer followed by max pooling and fully connected layers.
   - `iCNN`: Advanced Convolutional Neural Network with additional convolutional layers, max pooling, dropout, and fully connected layers for enhanced performance.

3. **Training and Evaluation Functions**:
   - `train`: Function to train the model on the provided dataset.
   - `evaluate`: Function to assess the model's accuracy on a test dataset.
   - `get_predictions`: Function to obtain model predictions for analysis.

4. **Model Training and Testing**:
   - Models are instantiated, trained using Adam optimizer and CrossEntropy loss, and evaluated based on accuracy and classification reports.

5. **Comparative Analysis**:
   - Performance comparison of different models focusing on training loss, test accuracy, and F1-Scores.

6. **Hyperparameter Experimentation**:
   - Analysis of the impact of learning rates on the iCNN model's performance.

7. **PDF Export**:
   - Code for converting the notebook into a PDF document for easy sharing and presentation.
