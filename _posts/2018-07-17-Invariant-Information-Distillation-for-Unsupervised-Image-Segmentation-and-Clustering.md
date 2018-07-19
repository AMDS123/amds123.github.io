---
layout: post
title: "Invariant Information Distillation for Unsupervised Image Segmentation and Clustering"
date: 2018-07-17 20:17:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding Semantic_Segmentation Classification Deep_Learning
author: Xu Ji, João F. Henriques, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new method that learns to segment and cluster images without labels of any kind. A simple loss based on information theory is used to extract meaningful representations directly from raw images. This is achieved by maximising mutual information of images known to be related by spatial proximity or randomized transformations, which distills their shared abstract content. Unlike much of the work in unsupervised deep learning, our learned function outputs segmentation heatmaps and discrete classifications labels directly, rather than embeddings that need further processing to be usable. The loss can be formulated as a convolution, making it the first end-to-end unsupervised learning method that learns densely and efficiently (i.e. without sampling) for semantic segmentation. Implemented using realistic settings on generic deep neural network architectures, our method attains superior performance on COCO-Stuff and ISPRS-Potsdam for segmentation and STL for clustering, beating state-of-the-art baselines.

##### Abstract (translated by Google)
我们提出了一种新方法，可以学习分割和聚类图像，而无需任何标签。基于信息理论的简单损失用于直接从原始图像中提取有意义的表示。这是通过最大化已知通过空间接近或随机变换相关的图像的互信息来实现的，这提取了它们共享的抽象内容。与无监督深度学习中的大部分工作不同，我们的学习函数直接输出分割热图和离散分类标签，而不是需要进一步处理才能使用的嵌入。损失可以表示为卷积，使其成为第一个端到端的无监督学习方法，它可以密集有效地学习（即无需采样）语义分割。通过在通用深度神经网络架构上使用现实设置实现，我们的方法在COCO-Stuff和ISPRS-Potsdam上获得了优越的性能，用于分段和STL用于聚类，击败了最先进的基线。

##### URL
[https://arxiv.org/abs/1807.06653](https://arxiv.org/abs/1807.06653)

##### PDF
[https://arxiv.org/pdf/1807.06653](https://arxiv.org/pdf/1807.06653)

