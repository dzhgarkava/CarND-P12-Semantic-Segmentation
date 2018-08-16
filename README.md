# Semantic Segmentation
Self-Driving Car Engineer Nanodegree Program
   
In this project I implemented a Fully Convolutional Network based on the VGG-16 image classifier architecture for road detection.
This network trained and tested on the KITTI dataset.

![alt text][image1]

![alt text][image2]

![alt text][image3]

![alt text][image4]

![alt text][image5]

![alt text][image6]

The network labels most pixels of road close to the best solution.

Base on several experiments I choose these hyperparameters:
- keep_prob: 0.5
- learning_rate: 0.0001
- epochs: 50
- batch_size: 5

Loading the pretrained vgg model made in load_vgg() method (main.py, lines: 20-45). 

Layers structure implemented in layers() method (main.py, line: 49-102).

For this network I use Adam optimizer (main.py, lines: 106-128).

[//]: # (Image References)
[image1]: ./images/example_1.png
[image2]: ./images/example_2.png
[image3]: ./images/example_3.png
[image4]: ./images/example_4.png
[image5]: ./images/example_5.png
[image6]: ./images/example_6.png