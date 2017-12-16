---
layout: post
title: "Learning Aerial Image Segmentation from Online Maps"
date: 2017-07-21 12:58:18
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification Deep_Learning
author: Pascal Kaiser, Jan Dirk Wegner, Aurelien Lucchi, Martin Jaggi, Thomas Hofmann, Konrad Schindler
mathjax: true
---

* content
{:toc}

##### Abstract
This study deals with semantic segmentation of high-resolution (aerial) images where a semantic class label is assigned to each pixel via supervised classification as a basis for automatic map generation. Recently, deep convolutional neural networks (CNNs) have shown impressive performance and have quickly become the de-facto standard for semantic segmentation, with the added benefit that task-specific feature design is no longer necessary. However, a major downside of deep learning methods is that they are extremely data-hungry, thus aggravating the perennial bottleneck of supervised classification, to obtain enough annotated training data. On the other hand, it has been observed that they are rather robust against noise in the training labels. This opens up the intriguing possibility to avoid annotating huge amounts of training data, and instead train the classifier from existing legacy data or crowd-sourced maps which can exhibit high levels of noise. The question addressed in this paper is: can training with large-scale, publicly available labels replace a substantial part of the manual labeling effort and still achieve sufficient performance? Such data will inevitably contain a significant portion of errors, but in return virtually unlimited quantities of it are available in larger parts of the world. We adapt a state-of-the-art CNN architecture for semantic segmentation of buildings and roads in aerial images, and compare its performance when using different training data sets, ranging from manually labeled, pixel-accurate ground truth of the same city to automatic training data derived from OpenStreetMap data from distant locations. We report our results that indicate that satisfying performance can be obtained with significantly less manual annotation effort, by exploiting noisy large-scale training data.

##### Abstract (translated by Google)
本研究涉及高分辨率（航空）图像的语义分割，其中通过监督分类将语义类别标签分配给每个像素作为自动地图生成的基础。最近，深度卷积神经网络（CNNs）已经显示出了令人印象深刻的性能，并且很快成为了语义分割的事实上的标准，另外的好处是不再需要任务特定的特征设计。然而，深度学习方法的一个主要缺点是极度数据饥饿，从而加重了监督分类的长期瓶颈，获得了足够的注释训练数据。另一方面，已经观察到它们在训练标签中对抗噪声是相当强健的。这为避免注释大量的训练数据开辟了有趣的可能性，而是从现有的遗留数据或可能表现出高水平噪声的众包地图训练分类器。本文所讨论的问题是：可以使用大规模公开可用的标签进行培训取代手动标签工作的实质性部分，并且仍然可以获得足够的性能？这样的数据将不可避免地包含很大一部分错误，但是在世界上大部分地区可以获得的数量实际上是无限的。我们采用先进的CNN体​​系结构对航拍图像中的建筑物和道路进行语义分割，并比较使用不同训练数据集时的性能，从同一城市的手动标记像素准确的地面真实到自动训练来自远方的来自OpenStreetMap数据的数据。我们报告我们的结果表明，通过利用嘈杂的大规模训练数据，可以用明显较少的手动注释努力获得令人满意的性能。

##### URL
[https://arxiv.org/abs/1707.06879](https://arxiv.org/abs/1707.06879)

##### PDF
[https://arxiv.org/pdf/1707.06879](https://arxiv.org/pdf/1707.06879)

