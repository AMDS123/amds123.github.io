---
layout: post
title: "Conditional Random Fields as Recurrent Neural Networks"
date: 2016-04-13 23:26:45
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation CNN Semantic_Segmentation Inference RNN Deep_Learning Recognition
author: Shuai Zheng, Sadeep Jayasumana, Bernardino Romera-Paredes, Vibhav Vineet, Zhizhong Su, Dalong Du, Chang Huang, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Pixel-level labelling tasks, such as semantic segmentation, play a central role in image understanding. Recent approaches have attempted to harness the capabilities of deep learning techniques for image recognition to tackle pixel-level labelling tasks. One central issue in this methodology is the limited capacity of deep learning techniques to delineate visual objects. To solve this problem, we introduce a new form of convolutional neural network that combines the strengths of Convolutional Neural Networks (CNNs) and Conditional Random Fields (CRFs)-based probabilistic graphical modelling. To this end, we formulate mean-field approximate inference for the Conditional Random Fields with Gaussian pairwise potentials as Recurrent Neural Networks. This network, called CRF-RNN, is then plugged in as a part of a CNN to obtain a deep network that has desirable properties of both CNNs and CRFs. Importantly, our system fully integrates CRF modelling with CNNs, making it possible to train the whole deep network end-to-end with the usual back-propagation algorithm, avoiding offline post-processing methods for object delineation. We apply the proposed method to the problem of semantic image segmentation, obtaining top results on the challenging Pascal VOC 2012 segmentation benchmark.

##### Abstract (translated by Google)
诸如语义分割之类的像素级标记任务在图像理解中起核心作用。最近的方法试图利用图像识别的深度学习技术的能力来处理像素级的标记任务。这种方法的一个核心问题是深度学习技术的能力有限，以描绘视觉对象。为了解决这个问题，我们引入了一种卷积神经网络的新形式，它结合了卷积神经网络（CNNs）和基于条件随机场（CRFs）的概率图形建模的优势。为此，我们将具有高斯成对电位的条件随机场作为递归神经网络的均值场近似推导。然后将这个称为CRF-RNN的网络作为CNN的一部分插入，以获得具有CNN和CRF的理想特性的深度网络。重要的是，我们的系统将CRF建模与CNN完全集成在一起，使得使用通常的反向传播算法来端到端地训练整个深度网络成为可能，避免了用于对象划分的离线后处理方法。我们将所提出的方法应用于语义图像分割问题，获得了具有挑战性的Pascal VOC 2012分割基准的最佳结果。

##### URL
[https://arxiv.org/abs/1502.03240](https://arxiv.org/abs/1502.03240)

##### PDF
[https://arxiv.org/pdf/1502.03240](https://arxiv.org/pdf/1502.03240)

