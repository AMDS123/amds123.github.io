---
layout: post
title: "Broadcasting Convolutional Network for Visual Relational Reasoning"
date: 2018-08-24 08:31:11
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Simyung Chang, John Yang, Seonguk Park, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose the Broadcasting Convolutional Network (BCN) that extracts key object features from the global field of an entire input image and recognizes their relationship with local features. BCN is a simple network module that collects effective spatial features, embeds location information and broadcasts them to the entire feature maps. We further introduce the Multi-Relational Network (multiRN) that improves the existing Relation Network (RN) by utilizing the BCN module. In pixel-based relation reasoning problems, with the help of BCN, multiRN extends the concept of `pairwise relations' in conventional RNs to `multiwise relations' by relating each object with multiple objects at once. This yields in O(n) complexity for n objects, which is a vast computational gain from RNs that take O(n^2). Through experiments, multiRN has achieved a state-of-the-art performance on CLEVR dataset, which proves the usability of BCN on relation reasoning problems.

##### Abstract (translated by Google)
在本文中，我们提出了广播卷积网络（BCN），它从整个输入图像的全局字段中提取关键对象特征，并识别它们与局部特征的关系。 BCN是一个简单的网络模块，它可以收集有效的空间要素，嵌入位置信息并将它们广播到整个要素图。我们进一步介绍了利用BCN模块改进现有关系网络（RN）的多关系网络（multiRN）。在基于像素的关系推理问题中，在BCN的帮助下，multiRN通过将每个对象与多个对象同时关联，将传统RN中的“成对关系”概念扩展为“多向关系”。这产生了n个对象的O（n）复杂度，这是来自RN的大量计算增益，其取O（n ^ 2）。通过实验，multiRN在CLEVR数据集上取得了最先进的性能，证明了BCN在关系推理问题上的可用性。

##### URL
[http://arxiv.org/abs/1712.02517](http://arxiv.org/abs/1712.02517)

##### PDF
[http://arxiv.org/pdf/1712.02517](http://arxiv.org/pdf/1712.02517)

