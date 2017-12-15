---
layout: post
title: "CUNet: A Compact Unsupervised Network for Image Classification"
date: 2016-07-06 11:56:52
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Gradient_Descent
author: Le Dong, Ling He, Gaipeng Kong, Qianni Zhang, Xiaochun Cao, Ebroul Izquierdo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a compact network called CUNet (compact unsupervised network) to counter the image classification challenge. Different from the traditional convolutional neural networks learning filters by the time-consuming stochastic gradient descent, CUNet learns the filter bank from diverse image patches with the simple K-means, which significantly avoids the requirement of scarce labeled training images, reduces the training consumption, and maintains the high discriminative ability. Besides, we propose a new pooling method named weighted pooling considering the different weight values of adjacent neurons, which helps to improve the robustness to small image distortions. In the output layer, CUNet integrates the feature maps gained in the last hidden layer, and straightforwardly computes histograms in non-overlapped blocks. To reduce feature redundancy, we implement the max-pooling operation on adjacent blocks to select the most competitive features. Comprehensive experiments are conducted to demonstrate the state-of-the-art classification performances with CUNet on CIFAR-10, STL-10, MNIST and Caltech101 benchmark datasets.

##### Abstract (translated by Google)
在本文中，我们提出一个称为CUNet（紧凑无监督网络）的紧凑网络来应对图像分类的挑战。与传统的卷积神经网络学习滤波器不同的是，耗时的随机梯度下降算法，CUNet以简单的K均值方法从不同的图像块中学习滤波器组，从而显着地避免了稀缺标记训练图像的需求，并保持高判别能力。此外，考虑到邻近神经元的权值不同，提出了一种新的加权池方法，有助于提高对小图像失真的鲁棒性。在输出层，CUNet集成了最后一个隐藏层获得的特征映射，并直接计算非重叠块中的直方图。为了减少特征冗余，我们对相邻块实施最大池操作，以选择最具竞争力的特征。在CIFAR-10，STL-10，MNIST和Caltech101基准数据集上进行综合实验，以证明CUNet的最新分类性能。

##### URL
[https://arxiv.org/abs/1607.01577](https://arxiv.org/abs/1607.01577)

##### PDF
[https://arxiv.org/pdf/1607.01577](https://arxiv.org/pdf/1607.01577)

