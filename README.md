# Semantic-Image-Segmentation-

## General project idea
Training and testing the dataset via Pytorch and Semantic Segmentation to identify and classify the objects from the static images. We will try to classify by using the label that the dataset provided, such as cars, humans, and other objects. We want to explore different architectures and compare them against the state of the art. (general idea: we want to identify different objects in pictures)

We seek to train and test the dataset via Pytorch and Semantic Segmentation to identify and classify the objects from the static images. This project will classify the object in the image by using the label that the dataset provided, such as cars, humans, and other objects. The target is to explore different architectures and compare them against the state of the art. After training the algorithm, we will use the algorithm to segment the images and see the accuracy of the segmentation algorithm.

We want to perform semantic segmentation on an image.We will take an image and predict which objects in the picture have which labels. We will also create the boundary and then classify it. We want to test different deep neural networks such as the CNN, R-CNN, etc.

Semantic Image segmentation seeks to label the pixels in an image with a particular class label. This differs from instance segmentation as instance segmentation seeks to separate each instance of the class while semantic segmentation doesn’t inherently distinguish between instances of a class. Eg, when examining a picture of two dogs, semantic segmentation would classify both as ‘dog’ whereas instance segmentation would classify the first dog from the second.

## Dataset
The PASCAL VOC[3] (Visual Object Classes) in 2012 dataset is large-scale object detection, segmentation, key-point detection, and captioning dataset. The Datasets for this project, we considered the training set of 1,968 images, the Validation set of 216 Images, and the testing set of 168 Images. For class indices for VOC labels, there are 21 colormaps for segmentation classes and 21 segmentation objects.
