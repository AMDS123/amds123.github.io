---
layout: post
title: "Eigen-Distortions of Hierarchical Representations"
date: 2017-11-04 12:12:25
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Prediction Recognition
author: Alexander Berardino, Johannes Ballé, Valero Laparra, Eero P. Simoncelli
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a method for comparing hierarchical image representations in terms of their ability to explain perceptual sensitivity in humans. Specifically, we utilize Fisher information to establish a model-derived prediction of sensitivity to local perturbations of an image. For a given image, we compute the eigenvectors of the Fisher information matrix with largest and smallest eigenvalues, corresponding to the model-predicted most- and least-noticeable image distortions, respectively. For human subjects, we then measure the amount of each distortion that can be reliably detected when added to the image, and compare these thresholds to the predictions of the corresponding model. We use this method to test the ability of a variety of representations to mimic human perceptual sensitivity. We find that the early layers of VGG16, a deep neural network optimized for object recognition, provide a better match to human perception than later layers, and a better match than a 4-stage convolutional neural network (CNN) trained on a database of human ratings of distorted image quality. On the other hand, we find that simple models of early visual processing, incorporating one or more stages of local gain control, trained on the same database of distortion ratings, provide substantially better predictions of human sensitivity than both the CNN and all layers of VGG16.

##### Abstract (translated by Google)
我们开发了一种方法来比较层次图像表示的能力来解释人类的感知灵敏度。具体而言，我们利用费希尔信息来建立模型对图像局部摄动敏感性的预测。对于给定的图像，我们计算Fisher信息矩阵的特征向量，其具有最大和最小的特征值，分别对应于模型预测的最大和最小可察觉的图像失真。对于人体，我们测量每个加到图像上时可以可靠检测的变形量，并将这些阈值与相应模型的预测值进行比较。我们用这种方法来测试各种表征模仿人类感知敏感的能力。我们发现早期的VGG16层是一种针对物体识别进行优化的深度神经网络，它比人类的感知更好地匹配后面的层次，并且比在人类数据库上训练的4级卷积神经网络（CNN）更好地匹配图像质量失真的评级。另一方面，我们发现早期视觉处理的简单模型，结合了一个或多个局部增益控制阶段，在相同的失真率数据库上进行训练，提供了比CNN和VGG16的所有层都更好的人体敏感性预测。

##### URL
[https://arxiv.org/abs/1710.02266](https://arxiv.org/abs/1710.02266)

##### PDF
[https://arxiv.org/pdf/1710.02266](https://arxiv.org/pdf/1710.02266)

