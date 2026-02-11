# Brain-Tumor-Detection
This is an image classification CNN project for binary classification of brain MRI scans to detect tumour.Class 1: (Tumor) YES, Class 0: (Tumor) NO

Overview:
This project builds a deep learning model to automatically detect Tumors from the MRI brain scans. CNN architecture used for this project is VGG16. Along with Early Stopping and Class weights.

Dataset:
The dataset is downloaded from Kaggle and using TensorFlow the data is preprocessed and split accordingly into Train,Val and Test splits

Tools and Techniques:
Python
TensorFlow
MatplotLib
Seaborn
SkLearn
Numpy
Pandas

Model Architecture:
Data Augmentation
Preprocess_Input
Convolution Base VGG16 with Trainable as False
Flatten Layer
DropOut Layer
Dense Layer --> Output

Results:
Training accuracy: 82%
Validation accuracy: 84%
Test Accuracy: 90% 
Loss: Binary CrossEntropy
Optimizer: Adam
Confusion Matrix for Test and validation data

