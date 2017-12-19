---
layout: post
title: "Layer-Specific Adaptive Learning Rates for Deep Networks"
date: 2015-10-15 16:31:46
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification Deep_Learning
author: Bharat Singh, Soham De, Yangmuzi Zhang, Thomas Goldstein, Gavin Taylor
mathjax: true
---

* content
{:toc}

##### Abstract
The increasing complexity of deep learning architectures is resulting in training time requiring weeks or even months. This slow training is due in part to vanishing gradients, in which the gradients used by back-propagation are extremely large for weights connecting deep layers (layers near the output layer), and extremely small for shallow layers (near the input layer); this results in slow learning in the shallow layers. Additionally, it has also been shown that in highly non-convex problems, such as deep neural networks, there is a proliferation of high-error low curvature saddle points, which slows down learning dramatically. In this paper, we attempt to overcome the two above problems by proposing an optimization method for training deep neural networks which uses learning rates which are both specific to each layer in the network and adaptive to the curvature of the function, increasing the learning rate at low curvature points. This enables us to speed up learning in the shallow layers of the network and quickly escape high-error low curvature saddle points. We test our method on standard image classification datasets such as MNIST, CIFAR10 and ImageNet, and demonstrate that our method increases accuracy as well as reduces the required training time over standard algorithms.

##### Abstract (translated by Google)
深度学习架构越来越复杂，导致培训时间需要数周甚至数月。这种慢速训练的部分原因是消失梯度，其中反向传播所使用的梯度对于连接深层（输出层附近的层）的权重非常大，对于浅层（输入层附近）极小。这导致浅层学习缓慢。此外，还表明在诸如深度神经网络的高度非凸面问题中，存在高误差低曲率鞍点的扩散，这显着降低了学习速度。在本文中，我们试图通过提出一种用于训练深度神经网络的优化方法来解决上述两个问题，该方法使用网络中每个层所特有的学习速率并且适应于函数的曲率，低曲率点。这使我们能够加速在网络浅层的学习，并迅速摆脱高误差的低曲率鞍点。我们在标准图像分类数据集（如MNIST，CIFAR10和ImageNet）上测试我们的方法，并证明我们的方法提高了准确性，并且减少了标准算法所需的训练时间。

##### URL
[https://arxiv.org/abs/1510.04609](https://arxiv.org/abs/1510.04609)

##### PDF
[https://arxiv.org/pdf/1510.04609](https://arxiv.org/pdf/1510.04609)

