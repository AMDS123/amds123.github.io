---
layout: post
title: "The Local Dimension of Deep Manifold"
date: 2017-11-05 12:17:35
categories: arXiv_CV
tags: arXiv_CV GAN CNN
author: Mengxiao Zhang, Wangquan Wu, Yanren Zhang, Kun He, Tao Yu, Huan Long, John E. Hopcroft
mathjax: true
---

* content
{:toc}

##### Abstract
Based on our observation that there exists a dramatic drop for the singular values of the fully connected layers or a single feature map of the convolutional layer, and that the dimension of the concatenated feature vector almost equals the summation of the dimension on each feature map, we propose a singular value decomposition (SVD) based approach to estimate the dimension of the deep manifolds for a typical convolutional neural network VGG19. We choose three categories from the ImageNet, namely Persian Cat, Container Ship and Volcano, and determine the local dimension of the deep manifolds of the deep layers through the tangent space of a target image. Through several augmentation methods, we found that the Gaussian noise method is closer to the intrinsic dimension, as by adding random noise to an image we are moving in an arbitrary dimension, and when the rank of the feature matrix of the augmented images does not increase we are very close to the local dimension of the manifold. We also estimate the dimension of the deep manifold based on the tangent space for each of the maxpooling layers. Our results show that the dimensions of different categories are close to each other and decline quickly along the convolutional layers and fully connected layers. Furthermore, we show that the dimensions decline quickly inside the Conv5 layer. Our work provides new insights for the intrinsic structure of deep neural networks and helps unveiling the inner organization of the black box of deep neural networks.

##### Abstract (translated by Google)
基于我们的观察，完全连通层的奇异值或卷积层的单个特征映射存在显着的下降，并且级联特征向量的维度几乎等于每个特征映射上维度的总和，我们提出了一种基于奇异值分解（SVD）的方法来估计典型卷积神经网络VGG19的深流形维数。我们从ImageNet中选择三个类别，即波斯猫，集装箱船和火山，并通过目标图像的切线空间确定深层深流形的局部维数。通过几种增强方法，我们发现高斯噪声方法更接近于固有维度，如随机噪声添加到我们正在任意维度移动的图像，并且当增强图像的特征矩阵的秩不增加我们非常接近歧管的局部维度。我们还根据每个最大层的切线空间估计深流形的维数。我们的研究结果表明，不同类别的维度彼此接近，并沿着卷积层和完全连通的层快速下降。此外，我们显示Conv5层内的尺寸迅速下降。我们的工作为深度神经网络的内在结构提供了新的见解，并有助于揭示深度神经网络黑盒的内部组织。

##### URL
[https://arxiv.org/abs/1711.01573](https://arxiv.org/abs/1711.01573)

##### PDF
[https://arxiv.org/pdf/1711.01573](https://arxiv.org/pdf/1711.01573)

