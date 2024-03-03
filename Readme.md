# Trash Image Classification
## This project aims to classify trash images into six categories: cardboard, glass, metal, paper, plastic, and trash. The dataset used for this classification task was collected from this repository.

### Overview
####The code performs the following tasks:

1- Imports: Necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Keras are imported.

2- Reading Data: Data is read from the specified directory, and file paths along with their respective classes are stored in a DataFrame.

3- Exploring Data: The distribution of classes in the dataset is visualized using a count plot. Random images from each class are also displayed to understand the variety of shapes and sizes.

4- Cleaning Data: The dataset is split into training and testing sets, ensuring a balanced distribution of classes. Data resizing and augmentation techniques are applied to prepare the images for training.

5- Creating Model: A simple Convolutional Neural Network (CNN) model is created using Keras with layers for convolution, max-pooling, dropout, flattening, and dense connections.

6- Training: The model is trained on the augmented training data with specified configurations such as batch size, epochs, and validation data. Model checkpoints are saved for the best weights during training.

7- Evaluating: Model performance is evaluated using metrics such as accuracy, precision, recall, and F1 score. A confusion matrix is also plotted to visualize the performance across different classes.

8- Transfer Learning: The possibility of transfer learning is explored by testing the trained model on new images in real-world scenarios.

#### For detailed implementation and usage instructions, please refer to the code comments and documentation within the respective files.

### This README provides a comprehensive overview of the Trash Image Classification project, including its purpose, functionality, and usage instructions. Further details can be found within the code itself.
