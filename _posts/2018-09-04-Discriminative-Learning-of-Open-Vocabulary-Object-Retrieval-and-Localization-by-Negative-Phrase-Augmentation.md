---
layout: post
title: "Discriminative Learning of Open-Vocabulary Object Retrieval and Localization by Negative Phrase Augmentation"
date: 2018-09-04 06:50:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Embedding Detection
author: Ryota Hinami, Shin&#x27;ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Thanks to the success of object detection technology, we can retrieve objects of the specified classes even from huge image collections. However, the current state-of-the-art object detectors (such as Faster R-CNN) can only handle pre-specified classes. In addition, large amounts of positive and negative visual samples are required for training. In this paper, we address the problem of open-vocabulary object retrieval and localization, where the target object is specified by a textual query (e.g., a word or phrase). We first propose Query-Adaptive R-CNN, a simple extension of Faster R-CNN adapted to open-vocabulary queries, by transforming the text embedding vector into an object classifier and localization regressor. Then, for discriminative training, we then propose negative phrase augmentation (NPA) to mine hard negative samples which are visually similar to the query and at the same time semantically mutually exclusive of the query. The proposed method can retrieve and localize objects specified by a textual query from one million images in only 0.5 seconds with high precision.

##### Abstract (translated by Google)
由于对象检测技术的成功，我们甚至可以从巨大的图像集合中检索指定类的对象。然而，当前最先进的物体检测器（例如更快的R-CNN）只能处理预先指定的类。此外，培训需要大量的阳性和阴性视觉样本。在本文中，我们解决了开放词汇对象检索和定位的问题，其中目标对象由文本查询（例如，单词或短语）指定。我们首先提出了Query-Adaptive R-CNN，它是一种适用于开放式词汇查询的Faster R-CNN的简单扩展，它通过将文本嵌入向量转换为对象分类器和本地化回归器。然后，为了进行区别性训练，我们然后提出消极短语增强（NPA）来挖掘硬视觉样本，这些样本在视觉上类似于查询并且同时在语义上与查询互斥。所提出的方法可以在0.5秒内以高精度从一百万个图像中检索和定位由文本查询指定的对象。

##### URL
[http://arxiv.org/abs/1711.09509](http://arxiv.org/abs/1711.09509)

##### PDF
[http://arxiv.org/pdf/1711.09509](http://arxiv.org/pdf/1711.09509)

