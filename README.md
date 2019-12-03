# Fashion MNIST Dataset Classification
**[Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)** is a dataset of Zalando's article images instead of hand-written digits like the old MNIST, in order to be a replacement benchmarking machine learning algorithms. This dataset contains **70.000** images: it consists of a training set of **60.0000** images and a test set of **10.000** images. Here's how the dataset looks like:

<p align="center">
  <img src="https://i.imgur.com/bkIfejC.png" alt="fashion MNIST image"/>
</p>
Each image is a 28x28 grayscale associated with a label from 10 different labels.
Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

# Objective
Our purpose is to use Convolutional Neural Networks to classify the dataset.
* [Simple CNN](http://nbviewer.jupyter.org/github/Alicia6N/fashion-mnist-cnn/blob/master/Basic-CNN-model.ipynb): Trained a simple CNN classifier with 1 convolution layer, max-pooling layers, dense layers and dropout layers. 91.37% accuracy.
* [Advanced CNN](http://nbviewer.jupyter.org/github/Alicia6N/fashion-mnist-cnn/blob/master/Advanced-CNN-model.ipynb): Trained a deeper CNN classifier with 4 convolution layers, max-pooling layers, dropout layers and batch normalization. 94.15% accuracy.
