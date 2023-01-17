# Vegetables-Classification

A simple vegetable classifier aiming to predict, given an input image, which class a certain vegetable contained in the image is part of. There are in total 15 classes, i.e. bean, bitter gourd, bottle gourd, brinjal, broccoli, cabbage, capsicum, carrot, cauliflower, cucumber, papaya, potato, pumpkin, radish and tomato. The [**Dataset**](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset) used is freely available on Kaggle and contains a total of 21,000 images already divided in Training, Validation and Test sets. 

We trained and tested two main classifiers: 
- the first based on an hand-crafted Convolutional Neural Network (CNN) inspired by the well-known [AlexNet](https://dl.acm.org/doi/abs/10.1145/3065386) 
- the second uses as base network a pre-trained [ResNet50](https://arxiv.org/abs/1512.03385) and an additional final fully-connected layer is added in order to perfor fine-tuning. 

The obtained results in terms of performances, learning curves, confusion matrix and classification errors are shown for each of the two classifiers.
In addition, the project is developed by using [Tensorflow](https://www.tensorflow.org/). 
