---
layout: post
title: "Performance Evaluation of Deep Learning Networks for Semantic Segmentation of Traffic Stereo-Pair Images"
date: 2018-06-05 19:00:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference Deep_Learning Relation
author: Vlad Taran, Nikita Gordienko, Yuriy Kochura, Yuri Gordienko, Alexandr Rokovyi, Oleg Alienin, Sergii Stirenko
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic image segmentation is one the most demanding task, especially for analysis of traffic conditions for self-driving cars. Here the results of application of several deep learning architectures (PSPNet and ICNet) for semantic image segmentation of traffic stereo-pair images are presented. The images from Cityscapes dataset and custom urban images were analyzed as to the segmentation accuracy and image inference time. For the models pre-trained on Cityscapes dataset, the inference time was equal in the limits of standard deviation, but the segmentation accuracy was different for various cities and stereo channels even. The distributions of accuracy (mean intersection over union - mIoU) values for each city and channel are asymmetric, long-tailed, and have many extreme outliers, especially for PSPNet network in comparison to ICNet network. Some statistical properties of these distributions (skewness, kurtosis) allow us to distinguish these two networks and open the question about relations between architecture of deep learning networks and statistical distribution of the predicted results (mIoU here). The results obtained demonstrated the different sensitivity of these networks to: (1) the local street view peculiarities in different cities that should be taken into account during the targeted fine tuning the models before their practical applications, (2) the right and left data channels in stereo-pairs. For both networks, the difference in the predicted results (mIoU here) for the right and left data channels in stereo-pairs is out of the limits of statistical error in relation to mIoU values. It means that the traffic stereo pairs can be effectively used not only for depth calculations (as it is usually used), but also as an additional data channel that can provide much more information about scene objects than simple duplication of the same street view images.

##### Abstract (translated by Google)
语义图像分割是最苛刻的任务之一，特别是分析自动驾驶汽车的交通状况。这里给出了几种深度学习体系结构（PSPNet和ICNet）在交通立体对图像语义图像分割中的应用结果。分析Cityscapes数据集和定制城市图像中的图像，分析图像的分割准确性和图像推理时间。对于Cityscapes数据集预先训练的模型，推断时间在标准偏差范围内是相等的，但对于不同的城市和立体声频道，分割准确度也是不同的。每个城市和频道的精确度分布（平均交叉点超过联盟 -  mIoU）值是不对称的，长尾的，并且有许多极端的异常值，特别是对于PSPNet网络而言，与ICNet网络相比。这些分布的某些统计特性（偏度，峰度）使我们能够区分这两个网络，并揭示深度学习网络的体系结构与预测结果的统计分布之间的关系问题（这里是mIoU）。所获得的结果表明，这些网络对于以下方面的不同敏感度：（1）在实际应用之前有针对性地对模型进行有针对性的微调时，不同城市中的当地街景特征;（2）右侧和左侧数据通道立体声对。对于这两个网络，立体对中左右数据通道的预测结果（此处为mIoU）的差异超出了与mIoU值有关的统计误差的限制。这意味着交通立体声对不仅可以有效地用于深度计算（如通常使用的那样），还可以作为附加数据通道提供更多有关场景对象的信息，而不仅仅是简单地复制相同的街景图像。

##### URL
[http://arxiv.org/abs/1806.01896](http://arxiv.org/abs/1806.01896)

##### PDF
[http://arxiv.org/pdf/1806.01896](http://arxiv.org/pdf/1806.01896)

