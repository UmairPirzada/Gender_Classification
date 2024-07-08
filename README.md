# Gender Classification Using Deep Learning
This repository contains implementations of various deep learning models to classify gender using a dataset of cropped images of males and females.

![image](https://github.com/UmairPirzada/Gender_Classification/assets/129576257/f12adbed-cab5-43cf-91a6-a2de27e16630)
# Dataset
The dataset consists of cropped images divided into training and validation directories:

# Training set:
~23,000 images of each class (male and female)

![image](https://github.com/UmairPirzada/Gender_Classification/assets/129576257/9f18b80f-8fcf-449d-82d0-b2fd7f0c9d71)


# Validation set:
~5,500 images of each class

![image](https://github.com/UmairPirzada/Gender_Classification/assets/129576257/1feb6aa9-1574-4fea-a1de-7f2f9ee77ec7)

# Models Implemented

### Sequential Model

### VGG16

### VGG19

### MobileNet

# Directory Structure

gender-classification-sequential.ipynb: Implementation of the sequential model. 

gender-classification-vgg-16.ipynb: Implementation of the VGG16 model.

gender-classification-vgg-19.ipynb: Implementation of the VGG19 model.

gender-classification-mobilenet.ipynb: Implementation of the MobileNet model.

# Requirements

### Python 3.x

### TensorFlow

### Keras

### NumPy

### Pandas

### Matplotlib

# Installation

### Clone the repository:
bash
Copy code
git clone https://github.com/UmairPirzada/Gender_Classification.git

# Usage
To run any of the models, open the respective Jupyter notebook and execute the cells. Make sure the dataset is properly placed in the directory structure as mentioned.

# Results
The results of each model are documented within their respective notebooks. Accuracy, loss, and other metrics are visualized using plots.

![image](https://github.com/UmairPirzada/Gender_Classification/assets/129576257/7a5f7883-9383-4636-8e18-7d0ec71bc658)

![image](https://github.com/UmairPirzada/Gender_Classification/assets/129576257/f44973a6-dc60-4e55-babc-68f3b5a179e3)

# Conclusion
In this project, four d ep learning models (Sequential, VGG16, VGG19, and MobileNet) were implemented to classify gender based on a dataset of cropped images. Each model demonstrated varying degrees of accuracy and performance, highlighting the strengths and weaknesses of different neural network architectures. This comparative analysis provides valuable insights for selecting appropriate models for image classification tasks, emphasizing the balance between model complexity and computational efficiency.
# Thank You!
