---
layout: post
title: "Efficient Facial Representations for Age, Gender and Identity Recognition in Organizing Photo Albums using Multi-output CNN"
date: 2018-07-20 07:12:36
categories: arXiv_CV
tags: arXiv_CV GAN Face CNN Prediction Recognition Face_Recognition
author: Andrey V. Savchenko
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is focused on the automatic extraction of persons and their attributes (gender, year of born) from album of photos and videos. We propose the two-stage approach, in which, firstly, the convolutional neural network simultaneously predicts age/gender from all photos and additionally extracts facial representations suitable for face identification. We modified the MobileNet, which is preliminarily trained to perform face recognition, in order to additionally recognize age and gender. In the second stage of our approach, extracted faces are grouped using hierarchical agglomerative clustering techniques. The born year and gender of a person in each cluster are estimated using aggregation of predictions for individual photos. We experimentally demonstrated that our facial clustering quality is competitive with the state-of-the-art neural networks, though our implementation is much computationally cheaper. Moreover, our approach is characterized by more accurate video-based age/gender recognition when compared to the publicly available models.

##### Abstract (translated by Google)
本文的重点是从照片和视频专辑中自动提取人员及其属性（性别，出生年份）。我们提出了两阶段方法，其中，首先，卷积神经网络同时预测所有照片的年龄/性别，并且另外提取适合于面部识别的面部表征。我们修改了MobileNet，它经过初步培训，可以进行人脸识别，以便进一步识别年龄和性别。在我们方法的第二阶段，使用分层凝聚聚类技术对提取的面部进行分组。使用单个照片的预测聚合来估计每个群集中的人的出生年份和性别。我们通过实验证明，我们的面部聚类质量与最先进的神经网络相比具有竞争力，尽管我们的实现在计算上更便宜。此外，与公开的模型相比，我们的方法的特点是基于视频的年龄/性别识别更准确。

##### URL
[http://arxiv.org/abs/1807.07718](http://arxiv.org/abs/1807.07718)

##### PDF
[http://arxiv.org/pdf/1807.07718](http://arxiv.org/pdf/1807.07718)

