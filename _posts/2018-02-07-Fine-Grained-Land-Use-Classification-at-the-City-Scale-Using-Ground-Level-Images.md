---
layout: post
title: "Fine-Grained Land Use Classification at the City Scale Using Ground-Level Images"
date: 2018-02-07 23:01:13
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Quantitative
author: Yi Zhu, Xueqing Deng, Shawn Newsam
mathjax: true
---

* content
{:toc}

##### Abstract
We perform fine-grained land use mapping at the city scale using ground-level images. Mapping land use is considerably more difficult than mapping land cover and is generally not possible using overhead imagery as it requires close-up views and seeing inside buildings. We postulate that the growing collections of georeferenced, ground-level images suggest an alternate approach to this geographic knowledge discovery problem. We develop a general framework that uses Flickr images to map 45 different land-use classes for the City of San Francisco. Individual images are classified using a novel convolutional neural network containing two streams, one for recognizing objects and another for recognizing scenes. This network is trained in an end-to-end manner directly on the labeled training images. We propose several strategies to overcome the noisiness of our user-generated data including search-based training set augmentation and online adaptive training. We derive a ground truth map of San Francisco in order to evaluate our method. We demonstrate the effectiveness of our approach through geo-visualization and quantitative analysis. Our framework achieves over 29% recall at the individual land parcel level which represents a strong baseline for the challenging 45-way land use classification problem especially given the noisiness of the image data.

##### Abstract (translated by Google)
我们使用地面图像在城市范围内进行细粒度的土地利用测绘。测绘土地使用比绘制土地覆盖要困难得多，而且通常不可能使用俯瞰图像，因为它需要特写视图和建筑物内部。我们假设，越来越多的地理参考地面图像的集合表明了这种地理知识发现问题的替代方法。我们开发了一个通用框架，使用Flickr图像来映射旧金山市45个不同的土地使用类。单个图像使用包含两个流的新型卷积神经网络进行分类，一个用于识别对象，另一个用于识别场景。该网络直接在标记的训练图像上以端对端的方式进行训练。我们提出了几种策略来克服用户生成的数据的嘈杂，包括基于搜索的训练集增强和在线自适应训练。我们推导了旧金山的地面实况地图，以评估我们的方法。我们通过地理可视化和定量分析证明了我们的方法的有效性。我们的框架在个别地块级别上实现了29％以上的回忆率，这对于具有挑战性的45路土地使用分类问题来说是一个很好的基准线，特别是考虑到图像数据的噪音。

##### URL
[http://arxiv.org/abs/1802.02668](http://arxiv.org/abs/1802.02668)

##### PDF
[http://arxiv.org/pdf/1802.02668](http://arxiv.org/pdf/1802.02668)

