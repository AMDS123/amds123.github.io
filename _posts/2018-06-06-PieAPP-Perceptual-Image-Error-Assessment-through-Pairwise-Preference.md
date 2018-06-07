---
layout: post
title: "PieAPP: Perceptual Image-Error Assessment through Pairwise Preference"
date: 2018-06-06 08:50:53
categories: arXiv_CV
tags: arXiv_CV
author: Ekta Prashnani, Hong Cai, Yasamin Mostofi, Pradeep Sen
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to estimate the perceptual error between images is an important problem in computer vision with many applications. Although it has been studied extensively, however, no method currently exists that can robustly predict visual differences like humans. Some previous approaches used hand-coded models, but they fail to model the complexity of the human visual system. Others used machine learning to train models on human-labeled datasets, but creating large, high-quality datasets is difficult because people are unable to assign consistent error labels to distorted images. In this paper, we present a new learning-based method that is the first to predict perceptual image error like human observers. Since it is much easier for people to compare two given images and identify the one more similar to a reference than to assign quality scores to each, we propose a new, large-scale dataset labeled with the probability that humans will prefer one image over another. We then train a deep-learning model using a novel, pairwise-learning framework to predict the preference of one distorted image over the other. Our key observation is that our trained network can then be used separately with only one distorted image and a reference to predict its perceptual error, without ever being trained on explicit human perceptual-error labels. The perceptual error estimated by our new metric, PieAPP, is well-correlated with human opinion. Furthermore, it significantly outperforms existing algorithms, beating the state-of-the-art by almost 3x on our test set in terms of binary error rate, while also generalizing to new kinds of distortions, unlike previous learning-based methods.

##### Abstract (translated by Google)
估计图像之间的感知误差的能力在许多应用中是计算机视觉中的重要问题。然而，尽管已经进行了广泛的研究，但是目前还没有能够强有力地预测人类视觉差异的方法。先前的一些方法使用手动编码模型，但它们未能模拟人类视觉系统的复杂性。其他人使用机器学习来训练人标记数据集上的模型，但创建大型高质量数据集非常困难，因为人们无法为扭曲图像分配一致的错误标签。在本文中，我们提出了一种新的基于学习的方法，它是第一个可以像人类观察者一样预测感知图像错误的方法。由于人们比较两个给定的图像比较容易，并且识别出与参考相比更接近参考的图像，而不是将质量分数分配给每个图像，所以我们提出了新的大规模数据集，其标记有人类将一个图像优先于另一个。然后，我们使用一种新颖的成对学习框架来训练一个深度学习模型，以预测一个扭曲图像相对于另一个扭曲图像的偏好。我们的关键观察结果是，我们的训练网络可以单独使用，只有一个失真的图像和一个参考来预测其感知错误，而不需要在显式的人类感知错误标签上进行训练。我们的新度量PieAPP估计的感知误差与人类意见密切相关。此外，与以前的基于学习的方法不同，它在性能上明显优于现有算法，在二进制错误率方面比我们的测试集高出近3倍，同时推广到新的失真类型。

##### URL
[http://arxiv.org/abs/1806.02067](http://arxiv.org/abs/1806.02067)

##### PDF
[http://arxiv.org/pdf/1806.02067](http://arxiv.org/pdf/1806.02067)

