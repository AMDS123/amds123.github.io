---
layout: post
title: "Walk and Learn: Facial Attribute Representation Learning from Egocentric Video and Contextual Data"
date: 2016-06-22 20:51:33
categories: arXiv_CV
tags: arXiv_CV Face Tracking Represenation_Learning Classification Prediction
author: Jing Wang, Yu Cheng, Rogerio Schmidt Feris
mathjax: true
---

* content
{:toc}

##### Abstract
The way people look in terms of facial attributes (ethnicity, hair color, facial hair, etc.) and the clothes or accessories they wear (sunglasses, hat, hoodies, etc.) is highly dependent on geo-location and weather condition, respectively. This work explores, for the first time, the use of this contextual information, as people with wearable cameras walk across different neighborhoods of a city, in order to learn a rich feature representation for facial attribute classification, without the costly manual annotation required by previous methods. By tracking the faces of casual walkers on more than 40 hours of egocentric video, we are able to cover tens of thousands of different identities and automatically extract nearly 5 million pairs of images connected by or from different face tracks, along with their weather and location context, under pose and lighting variations. These image pairs are then fed into a deep network that preserves similarity of images connected by the same track, in order to capture identity-related attribute features, and optimizes for location and weather prediction to capture additional facial attribute features. Finally, the network is fine-tuned with manually annotated samples. We perform an extensive experimental analysis on wearable data and two standard benchmark datasets based on web images (LFWA and CelebA). Our method outperforms by a large margin a network trained from scratch. Moreover, even without using manually annotated identity labels for pre-training as in previous methods, our approach achieves results that are better than the state of the art.

##### Abstract (translated by Google)
人们在面部特征（种族，头发颜色，面部毛发等）以及他们所穿的衣服或配饰（太阳镜，帽子，帽衫等）方面的方式高度依赖于地理位置和天气状况。这项工作首次探索使用这种上下文信息，因为具有可穿戴相机的人穿过城市的不同邻域，以便学习面部属性分类的丰富特征表示，而不需要以前需要的昂贵的手动注释方法。通过跟踪超过40小时的以自我为中心的视频的休闲步行者的面孔，我们能够覆盖数以万计的不同身份，并自动提取近500万对由不同面孔轨道连接的图像以及它们的天气和位置上下文，姿势和照明变化。然后将这些图像对馈送到深度网络中，以保留由相同轨道连接的图像的相似性，以捕获与身份有关的属性特征，并优化位置和天气预测以捕获额外的面部属性特征。最后，用手动注释的样本对网络进行微调。我们对可穿戴数据和基于网络图像（LFWA和CelebA）的两个标准基准数据集进行了广泛的实验分析。我们的方法远远优于从头开始培训的网络。而且，即使不像以前的方法那样使用手动注释的身份标签来进行预训练，我们的方法也达到了比现有技术更好的结果。

##### URL
[https://arxiv.org/abs/1604.06433](https://arxiv.org/abs/1604.06433)

##### PDF
[https://arxiv.org/pdf/1604.06433](https://arxiv.org/pdf/1604.06433)

