---
layout: post
title: "Cross-View Image Matching for Geo-localization in Urban Environments"
date: 2017-03-22 18:51:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection
author: Yicong Tian, Chen Chen, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of cross-view image geo-localization. Specifically, we aim to estimate the GPS location of a query street view image by finding the matching images in a reference database of geo-tagged bird's eye view images, or vice versa. To this end, we present a new framework for cross-view image geo-localization by taking advantage of the tremendous success of deep convolutional neural networks (CNNs) in image classification and object detection. First, we employ the Faster R-CNN to detect buildings in the query and reference images. Next, for each building in the query image, we retrieve the $k$ nearest neighbors from the reference buildings using a Siamese network trained on both positive matching image pairs and negative pairs. To find the correct NN for each query building, we develop an efficient multiple nearest neighbors matching method based on dominant sets. We evaluate the proposed framework on a new dataset that consists of pairs of street view and bird's eye view images. Experimental results show that the proposed method achieves better geo-localization accuracy than other approaches and is able to generalize to images at unseen locations.

##### Abstract (translated by Google)
在本文中，我们解决了交叉视图图像地理定位的问题。具体而言，我们旨在通过在具有地理标签的鸟瞰图图像的参考数据库中查找匹配图像来估计查询街景图像的GPS位置，反之亦然。为此，我们利用深度卷积神经网络（CNN）在图像分类和目标检测方面的巨大成功，提出了一种新的跨视点图像地理定位框架。首先，我们使用更快的R-CNN在查询和参考图像中检测建筑物。接下来，对于查询图像中的每个建筑物，我们使用在正匹配图像对和负对上训练的Siamese网络从参考建筑物中检索$ k $最近的邻居。为了找到每个查询建立正确的NN，我们开发了一个基于主导集的高效多重最近邻匹配方法。我们在一个新的数据集上评估提出的框架，该数据集由街景和鸟瞰图图像组成。实验结果表明，所提出的方法比其他方法具有更好的地理定位精度，能够将图像推广到不可见的位置。

##### URL
[https://arxiv.org/abs/1703.07815](https://arxiv.org/abs/1703.07815)

##### PDF
[https://arxiv.org/pdf/1703.07815](https://arxiv.org/pdf/1703.07815)

