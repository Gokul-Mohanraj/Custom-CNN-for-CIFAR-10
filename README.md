# CNN for the CIFAR-10 dataset

Here I have tried to create a basic Python code to classify the CIFAR-10 dataset. This dataset consists of 60000 images ( 10 classes, 6000 images per class). Each of the images has a size of 32 x 32 x 3 (for the RGB channels).

The highest test accuracy achieved on this data is using the All-Conv Network (95 %) that replaces the Pooling Layers with a stride 2 CNN. The model proposed here runs on a simple Deep CNN to achieve almost 90% accuracy on the testing set. The network has been written on a Google colaboratory notebook. The architecture is an adaptation of the famous LeNet architecture which uses Convolutional Layers to extract features and then classifies these feature vectors using a simple MLP network.

