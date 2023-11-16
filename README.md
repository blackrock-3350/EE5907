# EE5907 CA2

course project 2 of NUS EE5907

For the course project, students will work individually to construct a face recognition system. Students are required to apply Principal Component Analysis (PCA) to perform data dimensionality reduction and visualization, in order to understand underlying data distribution.

Then students are required to train and apply three classification models – Linear Discriminative Analysis (LDA), Support Vector Machine (SVM) and Convolutional Neural Networks (CNN) – to classify the face images, and one clustering model – Gaussian Mixture Model (GMM) – to group the face images. Through the project, students are expected to gain basic and important knowledge of currently popular pattern recognition techniques.

## Requirements

You need download `libsvm` and `PyTorch`.

- Python 3.11
- matplotlib == 3.7.1
- numpy == 1.24.3
- libsvm-official == 3.32.0
- torch == 2.1.0

see: [pip_list]() for more information.

## Dataset

We use CMU PIE dataset, and add 10 self photos.
In each jupyter notebook, datasets are
