---
layout: post
title: "Deep Label Distribution Learning with Label Ambiguity"
date: 2017-05-10 13:47:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation CNN Semantic_Segmentation Classification Recognition
author: Bin-Bin Gao, Chao Xing, Chen-Wei Xie, Jianxin Wu, Xin Geng
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (ConvNets) have achieved excellent recognition performance in various visual recognition tasks. A large labeled training set is one of the most important factors for its success. However, it is difficult to collect sufficient training images with precise labels in some domains such as apparent age estimation, head pose estimation, multi-label classification and semantic segmentation. Fortunately, there is ambiguous information among labels, which makes these tasks different from traditional classification. Based on this observation, we convert the label of each image into a discrete label distribution, and learn the label distribution by minimizing a Kullback-Leibler divergence between the predicted and ground-truth label distributions using deep ConvNets. The proposed DLDL (Deep Label Distribution Learning) method effectively utilizes the label ambiguity in both feature learning and classifier learning, which help prevent the network from over-fitting even when the training set is small. Experimental results show that the proposed approach produces significantly better results than state-of-the-art methods for age estimation and head pose estimation. At the same time, it also improves recognition performance for multi-label classification and semantic segmentation tasks.

##### Abstract (translated by Google)
卷积神经网络（ConvNets）在各种视觉识别任务中取得了优异的识别性能。一个大标签的训练集是成功的最重要的因素之一。然而，在明显的年龄估计，头部姿态估计，多标签分类和语义分割等领域，很难收集到具有精确标签的足够的训练图像。幸运的是，标签之间存在模糊的信息，这使得这些任务与传统分类不同。基于这个观察，我们将每幅图像的标签转换成一个离散的标签分布，并通过使用深度ConvNets来最小化预测和地面真值标签分布之间的Kullback-Leibler散度来学习标签分布。所提出的DLDL（深度标签分布式学习）方法在特征学习和分类器学习中有效地利用了标签模糊性，即使在训练集较小的情况下也有助于防止网络过度拟合。实验结果表明，所提出的方法产生比用于年龄估计和头部姿态估计的现有技术方法显着更好的结果。同时也提高了多标签分类和语义分割任务的识别性能。

##### URL
[https://arxiv.org/abs/1611.01731](https://arxiv.org/abs/1611.01731)

##### PDF
[https://arxiv.org/pdf/1611.01731](https://arxiv.org/pdf/1611.01731)

