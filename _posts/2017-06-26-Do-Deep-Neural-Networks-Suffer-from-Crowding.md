---
layout: post
title: "Do Deep Neural Networks Suffer from Crowding?"
date: 2017-06-26 22:25:56
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Anna Volokitin, Gemma Roig, Tomaso Poggio
mathjax: true
---

* content
{:toc}

##### Abstract
Crowding is a visual effect suffered by humans, in which an object that can be recognized in isolation can no longer be recognized when other objects, called flankers, are placed close to it. In this work, we study the effect of crowding in artificial Deep Neural Networks for object recognition. We analyze both standard deep convolutional neural networks (DCNNs) as well as a new version of DCNNs which is 1) multi-scale and 2) with size of the convolution filters change depending on the eccentricity wrt to the center of fixation. Such networks, that we call eccentricity-dependent, are a computational model of the feedforward path of the primate visual cortex. Our results reveal that the eccentricity-dependent model, trained on target objects in isolation, can recognize such targets in the presence of flankers, if the targets are near the center of the image, whereas DCNNs cannot. Also, for all tested networks, when trained on targets in isolation, we find that recognition accuracy of the networks decreases the closer the flankers are to the target and the more flankers there are. We find that visual similarity between the target and flankers also plays a role and that pooling in early layers of the network leads to more crowding. Additionally, we show that incorporating the flankers into the images of the training set does not improve performance with crowding.

##### Abstract (translated by Google)
拥挤是人类受到的一种视觉效应，当其他物体（称为侧翼）靠近它时，可以不再识别可以孤立识别的物体。在这项工作中，我们研究了人工深度神经网络中的拥挤对物体识别的影响。我们分析了标准的深度卷积神经网络（DCNN）和一个新版本的DCNN，它们是：1）多尺度的; 2）卷积滤波器的尺寸随离心率的变化而变化。这种网络，我们称之为偏心依赖，是灵长类动物视觉皮层前馈路径的计算模型。我们的研究结果表明，偏心依赖模型，孤立的目标对象的训练，可以识别这样的目标，如果目标是靠近图像中心，而DCNNs不能。而且，对于所有测试过的网络，当单独对目标进行训练时，我们发现网络的识别精度越低，侧翼越靠近目标，侧翼就越多。我们发现目标和侧翼之间的视觉相似性也起到了一定的作用，网络早期阶层的集中导致更多的拥挤。此外，我们表明，将侧翼并入训练集的图像并不能改善拥挤的性能。

##### URL
[https://arxiv.org/abs/1706.08616](https://arxiv.org/abs/1706.08616)

##### PDF
[https://arxiv.org/pdf/1706.08616](https://arxiv.org/pdf/1706.08616)

