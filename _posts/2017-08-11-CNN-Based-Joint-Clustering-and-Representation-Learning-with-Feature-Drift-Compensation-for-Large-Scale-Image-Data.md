---
layout: post
title: "CNN-Based Joint Clustering and Representation Learning with Feature Drift Compensation for Large-Scale Image Data"
date: 2017-08-11 07:31:48
categories: arXiv_CV
tags: arXiv_CV CNN Represenation_Learning Gradient_Descent
author: Chih-Chung Hsu, Chia-Wen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Given a large unlabeled set of images, how to efficiently and effectively group them into clusters based on extracted visual representations remains a challenging problem. To address this problem, we propose a convolutional neural network (CNN) to jointly solve clustering and representation learning in an iterative manner. In the proposed method, given an input image set, we first randomly pick k samples and extract their features as initial cluster centroids using the proposed CNN with an initial model pre-trained from the ImageNet dataset. Mini-batch k-means is then performed to assign cluster labels to individual input samples for a mini-batch of images randomly sampled from the input image set until all images are processed. Subsequently, the proposed CNN simultaneously updates the parameters of the proposed CNN and the centroids of image clusters iteratively based on stochastic gradient descent. We also proposed a feature drift compensation scheme to mitigate the drift error caused by feature mismatch in representation learning. Experimental results demonstrate the proposed method outperforms start-of-the-art clustering schemes in terms of accuracy and storage complexity on large-scale image sets containing millions of images.

##### Abstract (translated by Google)
给定大量未标记的图像集，如何有效和有效地将它们分组为基于提取的视觉表示的集群仍然是一个具有挑战性的问题。为了解决这个问题，我们提出了一个卷积神经网络（CNN），以迭代方式联合求解聚类和表示学习。在提出的方法中，给定一个输入图像集，我们首先随机选取k个样本，并使用提出的CNN和从ImageNet数据集预训练的初始模型提取它们的特征作为初始聚类质心。然后执行小批量k-均值，以将簇标签分配给从输入图像集随机采样的小批量图像的单个输入样本，直到处理完所有图像。随后，提出的CNN基于随机梯度下降同时更新提出的CNN的参数和图像簇的质心。我们还提出了一种特征漂移补偿方案来减轻表征学习中由于特征不匹配造成的漂移误差。实验结果表明，所提出的方法在包含数百万图像的大规模图像集上的精度和存储复杂度方面优于开始的最先进的聚类方案。

##### URL
[https://arxiv.org/abs/1705.07091](https://arxiv.org/abs/1705.07091)

##### PDF
[https://arxiv.org/pdf/1705.07091](https://arxiv.org/pdf/1705.07091)

