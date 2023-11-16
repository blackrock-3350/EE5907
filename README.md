# EE5907 CA2

course project 2 of NUS EE5907

For the course project, students will work individually to construct a face recognition system. Students are required to apply Principal Component Analysis `PCA` to perform data dimensionality reduction and visualization, in order to understand underlying data distribution.

Then students are required to train and apply three classification models – Linear Discriminative Analysis `LDA`, Support Vector Machine `SVM` and Convolutional Neural Networks `CNN` – to classify the face images. Through the project, students are expected to gain basic and important knowledge of currently popular pattern recognition techniques.

For [more information](https://drive.google.com/drive/folders/1Y9CfVH-NCxgkiNEHp7Mxsutd71uebtFW?usp=share_link), please refer to the CA PDF.

## Requirements

You need additionally download `libsvm` and `PyTorch`.

- Python == 3.11
- matplotlib == 3.7.1
- numpy == 1.24.3
- libsvm-official == 3.32.0
- torch == 2.1.0

see: [pip_list](https://github.com/blackrock-3350/EE5907_CA2/blob/main/pip_list) for more information.

## Dataset

We use CMU PIE dataset, and add 10 self photos. 
In each jupyter notebook, the paths to the dataset are similar. You can also change it easily in the code.

```
pie_path = r'D:\University\NUS\EE5907\PIE'
self_path = r'D:\University\NUS\EE5907\self'
path = r'D:\University\NUS\EE5907\PIE1' #25+1 selected subjects in this new dataset
```

### Attention! 
The use of absolute paths may result in denial of access. Try using a relative path or start jupyter with administrator privileges!

## IT JUST WORKS!

There were some potential errors in the code for this project and the classifier performance was not as good as it could have been at some points. XD
