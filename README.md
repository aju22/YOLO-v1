# YOLO-v1

YOLO stands for You Only Look Once. As the name says, network only looks the image once to detect multiple objects. This is a state-of-the-art deep learning object detection approach which has been published in 2016 CVPR by Joseph Redmon, Santosh Divvala, Ross Girshick, Ali Farhadi.

Find the research paper : [You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640)

This notebook is an implementation of YOLO-v1, built entirely from scratch using Tensorflow-Keras.
It was an attempt to fully understand the model architecture, intuition behind the network and the Yolo Loss function.

However, this notebook also contains utility classes for generating custom training data and evaluating the model, plotting the prediction etc., incase anybody wants to train the model from scratch and modify on top of it.
