# Residual Neural Network for image classification

![Logo](https://github.com/tharangachaminda/cnn_sign_language_detection/blob/main/dataset-cover.png)

Very deep neural networks suffer from a problem called **vanishing/exploding gradients**. In the year 2015 Kaiming He, et al proposed a solution for this in their research paper [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385.pdf). A Residual Network, also known as *ResNet*, is a type of deep learning network architecture that introduces the concept of *residual learning*.

In this project I will be implementing a ResNet using ResNet50 architecture which consists of 50 layers.

### Data Sources
This project is based on **SIGNS** dataset. This SIGNS dataset is a collection of 6 signs representing numbers from 0 to 5.

### Technologies and Tools
- Tensorflow
- Keras


## Installation

I have used [TensorFlow](https://www.tensorflow.org/) framework for this project. 

```bash
pip install tensorflow
```
    
## 🏆 Lessons Learned

1. Creat dataset from a directory
2. Preprocess and augment data using the Sequential API
3. Adapt a pretrained model to new data and train a classifier using the functional API MobileNet
4. Fine-tune a classifier's final layer to improve accuracy


