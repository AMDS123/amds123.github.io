---
layout: post
title: "Dynamic Action Recognition: A convolutional neural network model for temporally organized joint location data"
date: 2016-12-20 15:20:28
categories: arXiv_CV
tags: arXiv_CV GAN Action_Recognition CNN RNN Recognition
author: Adhavan Jayabalan, Harish Karunakaran, Shravan Murlidharan, Tesia Shizume
mathjax: true
---

* content
{:toc}

##### Abstract
Motivation: Recognizing human actions in a video is a challenging task which has applications in various fields. Previous works in this area have either used images from a 2D or 3D camera. Few have used the idea that human actions can be easily identified by the movement of the joints in the 3D space and instead used a Recurrent Neural Network (RNN) for modeling. Convolutional neural networks (CNN) have the ability to recognise even the complex patterns in data which makes it suitable for detecting human actions. Thus, we modeled a CNN which can predict the human activity using the joint data. Furthermore, using the joint data representation has the benefit of lower dimensionality than image or video representations. This makes our model simpler and faster than the RNN models. In this study, we have developed a six layer convolutional network, which reduces each input feature vector of the form 15x1961x4 to an one dimensional binary vector which gives us the predicted activity. Results: Our model is able to recognise an activity correctly upto 87% accuracy. Joint data is taken from the Cornell Activity Datasets which have day to day activities like talking, relaxing, eating, cooking etc.

##### Abstract (translated by Google)
动机：认识到人类在视频中的行为是一项具有挑战性的任务，在各个领域都有应用。以前在这个领域的作品要么使用2D或3D相机的图像。很少有人使用这样的想法，人类的行为可以很容易地通过关节在三维空间中的运动来识别，而是使用递归神经网络（RNN）进行建模。卷积神经网络（CNN）甚至能够识别数据中的复杂模式，使其适合于检测人的行为。因此，我们模拟了一个可以用联合数据预测人类活动的CNN。此外，使用联合数据表示具有比图像或视频表示更低的维度的益处。这使得我们的模型比RNN模型更简单，更快速。在这项研究中，我们已经开发了一个六层卷积网络，它将15x1961x4形式的每个输入特征向量减少到一个给定预测活动的一维二元向量。结果：我们的模型能够正确识别高达87％的活动。联合数据来自康奈尔活动数据集，这些活动数据集有日常活动，如说话，放松，进食，烹饪等。

##### URL
[https://arxiv.org/abs/1612.06703](https://arxiv.org/abs/1612.06703)

##### PDF
[https://arxiv.org/pdf/1612.06703](https://arxiv.org/pdf/1612.06703)

