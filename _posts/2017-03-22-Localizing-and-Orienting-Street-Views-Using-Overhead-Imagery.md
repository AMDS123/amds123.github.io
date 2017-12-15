---
layout: post
title: "Localizing and Orienting Street Views Using Overhead Imagery"
date: 2017-03-22 23:49:57
categories: arXiv_CV
tags: arXiv_CV Embedding Classification Prediction
author: Nam Vo, James Hays
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we aim to determine the location and orientation of a ground-level query image by matching to a reference database of overhead (e.g. satellite) images. For this task we collect a new dataset with one million pairs of street view and overhead images sampled from eleven U.S. cities. We explore several deep CNN architectures for cross-domain matching -- Classification, Hybrid, Siamese, and Triplet networks. Classification and Hybrid architectures are accurate but slow since they allow only partial feature precomputation. We propose a new loss function which significantly improves the accuracy of Siamese and Triplet embedding networks while maintaining their applicability to large-scale retrieval tasks like image geolocalization. This image matching task is challenging not just because of the dramatic viewpoint difference between ground-level and overhead imagery but because the orientation (i.e. azimuth) of the street views is unknown making correspondence even more difficult. We examine several mechanisms to match in spite of this -- training for rotation invariance, sampling possible rotations at query time, and explicitly predicting relative rotation of ground and overhead images with our deep networks. It turns out that explicit orientation supervision also improves location prediction accuracy. Our best performing architectures are roughly 2.5 times as accurate as the commonly used Siamese network baseline.

##### Abstract (translated by Google)
在本文中，我们旨在通过匹配到开销（例如卫星）图像的参考数据库来确定地面查询图像的位置和方向。为此，我们收集了一个新的数据集，其中包含从美国11个城市采集的100万对街景和高架图像。我们探索了多个CNN架构的跨域匹配 - 分类，混合，连体和三重网络。分类和混合体系结构是准确的，但是由于它们只允许部分特征预计算，所以速度很慢。我们提出了一个新的损失函数，显着提高了连体和三重网络嵌入网络的准确性，同时保持它们适用于图像地理定位这样的大规模检索任务。这种图像匹配任务是具有挑战性的，不仅仅是因为地面和俯视图像之间的戏剧性视点差异，而且因为街景的方向（即方位角）是未知的，所以对应更加困难。尽管如此，我们研究了几种匹配机制 - 旋转不变性的训练，在查询时间取样可能的旋转，以及用我们的深度网络明确地预测地面和俯视图像的相对旋转。事实证明，明确的定向监督也提高了位置预测的准确性。我们表现​​最好的体系结构大约是常用的连体网络基线的2.5倍。

##### URL
[https://arxiv.org/abs/1608.00161](https://arxiv.org/abs/1608.00161)

##### PDF
[https://arxiv.org/pdf/1608.00161](https://arxiv.org/pdf/1608.00161)

