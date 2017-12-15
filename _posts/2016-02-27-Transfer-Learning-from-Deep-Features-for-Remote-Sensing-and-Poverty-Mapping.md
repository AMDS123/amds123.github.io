---
layout: post
title: "Transfer Learning from Deep Features for Remote Sensing and Poverty Mapping"
date: 2016-02-27 23:21:48
categories: arXiv_CV
tags: arXiv_CV Sparse Survey CNN Transfer_Learning Prediction
author: Michael Xie, Neal Jean, Marshall Burke, David Lobell, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
The lack of reliable data in developing countries is a major obstacle to sustainable development, food security, and disaster relief. Poverty data, for example, is typically scarce, sparse in coverage, and labor-intensive to obtain. Remote sensing data such as high-resolution satellite imagery, on the other hand, is becoming increasingly available and inexpensive. Unfortunately, such data is highly unstructured and currently no techniques exist to automatically extract useful insights to inform policy decisions and help direct humanitarian efforts. We propose a novel machine learning approach to extract large-scale socioeconomic indicators from high-resolution satellite imagery. The main challenge is that training data is very scarce, making it difficult to apply modern techniques such as Convolutional Neural Networks (CNN). We therefore propose a transfer learning approach where nighttime light intensities are used as a data-rich proxy. We train a fully convolutional CNN model to predict nighttime lights from daytime imagery, simultaneously learning features that are useful for poverty prediction. The model learns filters identifying different terrains and man-made structures, including roads, buildings, and farmlands, without any supervision beyond nighttime lights. We demonstrate that these learned features are highly informative for poverty mapping, even approaching the predictive performance of survey data collected in the field.

##### Abstract (translated by Google)
发展中国家缺乏可靠的数据是可持续发展，粮食安全和救灾的主要障碍。例如，贫困数据通常很稀少，覆盖范围很少，而且劳动密集。另一方面，诸如高分辨率卫星图像的遥感数据变得越来越可用且便宜。不幸的是，这些数据是非常结构化的，目前还没有技术可以自动提取有用的见解来为政策决策提供信息，并有助于直接的人道主义努我们提出了一种新的机器学习方法，从高分辨率的卫星图像中提取大规模的社会经济指标。主要挑战是培训数据非常稀缺，难以应用现代技术，如卷积神经网络（CNN）。因此，我们提出了一种转换学习方法，将夜间光照强度用作数据丰富的代理。我们训练完全卷积CNN模型来预测白天图像的夜间灯光，同时学习对贫困预测有用的特征。该模型学习识别不同地形和人造建筑物的过滤器，包括道路，建筑物和农田，不受夜间照明之外的任何监督。我们证明这些学习功能对于贫困测绘是非常有益的，甚至可以接近实地收集的调查数据的预测性能。

##### URL
[https://arxiv.org/abs/1510.00098](https://arxiv.org/abs/1510.00098)

##### PDF
[https://arxiv.org/pdf/1510.00098](https://arxiv.org/pdf/1510.00098)

