---
layout: post
title: "Mixture separability loss in a deep convolutional network for image classification"
date: 2019-06-16 01:45:57
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Trung Dung Do, Cheng-Bin Jin, Hakil Kim, Van Huan Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
In machine learning, the cost function is crucial because it measures how good or bad a system is. In image classification, well-known networks only consider modifying the network structures and applying cross-entropy loss at the end of the network. However, using only cross-entropy loss causes a network to stop updating weights when all training images are correctly classified. This is the problem of the early saturation. This paper proposes a novel cost function, called mixture separability loss (MSL), which updates the weights of the network even when most of the training images are accurately predicted. MSL consists of between-class and within-class loss. Between-class loss maximizes the differences between inter-class images, whereas within-class loss minimizes the similarities between intra-class images. We designed the proposed loss function to attach to different convolutional layers in the network in order to utilize intermediate feature maps. Experiments show that a network with MSL deepens the learning process and obtains promising results with some public datasets, such as Street View House Number (SVHN), Canadian Institute for Advanced Research (CIFAR), and our self-collected Inha Computer Vision Lab (ICVL) gender dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06633](http://arxiv.org/abs/1906.06633)

##### PDF
[http://arxiv.org/pdf/1906.06633](http://arxiv.org/pdf/1906.06633)

