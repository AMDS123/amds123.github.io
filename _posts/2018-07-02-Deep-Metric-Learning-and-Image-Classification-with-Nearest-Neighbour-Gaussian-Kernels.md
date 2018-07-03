---
layout: post
title: "Deep Metric Learning and Image Classification with Nearest Neighbour Gaussian Kernels"
date: 2018-07-02 06:18:57
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Image_Classification Classification
author: Benjamin J. Meyer, Ben Harwood, Tom Drummond
mathjax: true
---

* content
{:toc}

##### Abstract
We present a Gaussian kernel loss function and training algorithm for convolutional neural networks that can be directly applied to both distance metric learning and image classification problems. Our method treats all training features from a deep neural network as Gaussian kernel centres and computes loss by summing the influence of a feature's nearby centres in the feature embedding space. Our approach is made scalable by treating it as an approximate nearest neighbour search problem. We show how to make end-to-end learning feasible, resulting in a well formed embedding space, in which semantically related instances are likely to be located near one another, regardless of whether or not the network was trained on those classes. Our approach outperforms state-of-the-art deep metric learning approaches on embedding learning challenges, as well as conventional softmax classification on several datasets.

##### Abstract (translated by Google)
我们提出了一种卷积神经网络的高斯核丢失函数和训练算法，可以直接应用于距离度量学习和图像分类问题。我们的方法将来自深度神经网络的所有训练特征视为高斯核心，并通过对特征嵌入空间中特征的附近中心的影响求和来计算损失。通过将其视为近似最近邻搜索问题，我们的方法可扩展。我们展示了如何使端到端学习成为可能，从而形成一个良好形成的嵌入空间，其中语义相关的实例可能彼此靠近，无论网络是否在这些类上进行了训练。我们的方法优于嵌入学习挑战的最先进的深度量学习方法，以及几个数据集上的传统softmax分类。

##### URL
[http://arxiv.org/abs/1705.09780](http://arxiv.org/abs/1705.09780)

##### PDF
[http://arxiv.org/pdf/1705.09780](http://arxiv.org/pdf/1705.09780)

