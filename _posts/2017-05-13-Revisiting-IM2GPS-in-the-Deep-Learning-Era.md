---
layout: post
title: "Revisiting IM2GPS in the Deep Learning Era"
date: 2017-05-13 14:43:02
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Deep_Learning
author: Nam Vo, Nathan Jacobs, James Hays
mathjax: true
---

* content
{:toc}

##### Abstract
Image geolocalization, inferring the geographic location of an image, is a challenging computer vision problem with many potential applications. The recent state-of-the-art approach to this problem is a deep image classification approach in which the world is spatially divided into cells and a deep network is trained to predict the correct cell for a given image. We propose to combine this approach with the original Im2GPS approach in which a query image is matched against a database of geotagged images and the location is inferred from the retrieved set. We estimate the geographic location of a query image by applying kernel density estimation to the locations of its nearest neighbors in the reference database. Interestingly, we find that the best features for our retrieval task are derived from networks trained with classification loss even though we do not use a classification approach at test time. Training with classification loss outperforms several deep feature learning methods (e.g. Siamese networks with contrastive of triplet loss) more typical for retrieval applications. Our simple approach achieves state-of-the-art geolocalization accuracy while also requiring significantly less training data.

##### Abstract (translated by Google)
图像地理定位，推断图像的地理位置，是一个具有挑战性的计算机视觉问题，有许多潜在的应用。针对这个问题的最新的最新方法是深度图像分类方法，其中将世界空间划分为单元格，并且训练深度网络以预测给定图像的正确单元格。我们建议将这种方法与最初的Im2GPS方法相结合，在这种方法中，将查询图像与地理标记图像的数据库进行匹配，并从检索的集合中推断出位置。我们通过将核密度估计应用到参考数据库中最近邻居的位置来估计查询图像的地理位置。有趣的是，我们发现我们的检索任务的最佳特征是从分类丢失训练的网络派生的，尽管我们在测试时不使用分类方法。具有分类损失的训练优于几种比较典型的用于检索应用的深度特征学习方法（例如，具有三重丢失对比的连体网络）。我们简单的方法实现了最先进的地理定位精度，同时也需要大大减少训练数据。

##### URL
[https://arxiv.org/abs/1705.04838](https://arxiv.org/abs/1705.04838)

##### PDF
[https://arxiv.org/pdf/1705.04838](https://arxiv.org/pdf/1705.04838)

