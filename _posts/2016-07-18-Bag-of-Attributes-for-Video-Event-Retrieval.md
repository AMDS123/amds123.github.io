---
layout: post
title: "Bag of Attributes for Video Event Retrieval"
date: 2016-07-18 17:24:23
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Leonardo A. Duarte, Otávio A. B. Penatti, Jurandy Almeida
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present the Bag-of-Attributes (BoA) model for video representation aiming at video event retrieval. The BoA model is based on a semantic feature space for representing videos, resulting in high-level video feature vectors. For creating a semantic space, i.e., the attribute space, we can train a classifier using a labeled image dataset, obtaining a classification model that can be understood as a high-level codebook. This model is used to map low-level frame vectors into high-level vectors (e.g., classifier probability scores). Then, we apply pooling operations on the frame vectors to create the final bag of attributes for the video. In the BoA representation, each dimension corresponds to one category (or attribute) of the semantic space. Other interesting properties are: compactness, flexibility regarding the classifier, and ability to encode multiple semantic concepts in a single video representation. Our experiments considered the semantic space created by a deep convolutional neural network (OverFeat) pre-trained on 1000 object categories of ImageNet. OverFeat was then used to classify each video frame and max pooling combined the frame vectors in the BoA representation for the video. Results using BoA outperformed the baselines with statistical significance in the task of video event retrieval using the EVVE dataset.

##### Abstract (translated by Google)
在本文中，我们针对视频事件检索提出视频表示的Bag-of-Attributes（BoA）模型。 BoA模型基于用于表示视频的语义特征空间，导致高级视频特征向量。为了创建语义空间，即属性空间，我们可以使用标记的图像数据集来训练分类器，从而获得可以被理解为高级码本的分类模型。该模型用于将低级帧向量映射到高级向量（例如，分类器概率分数）。然后，我们在帧矢量上应用池操作来创建视频的最终属性包。在BoA表示中，每个维度对应于语义空间的一个类别（或属性）。其他有趣的特性是：紧凑性，关于分类器的灵活性，以及​​在单个视频表示中编码多个语义概念的能力。我们的实验考虑了由深度卷积神经网络（OverFeat）在1000个对象类别的ImageNet上预先训练的语义空间。然后使用OverFeat对每个视频帧进行分类，最大池将视频的BoA表示中的帧矢量组合起来。在使用EVVE数据集的视频事件检索任务中，使用BoA的结果优于具有统计显着性的基线。

##### URL
[https://arxiv.org/abs/1607.05208](https://arxiv.org/abs/1607.05208)

##### PDF
[https://arxiv.org/pdf/1607.05208](https://arxiv.org/pdf/1607.05208)

