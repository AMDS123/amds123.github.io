---
layout: post
title: "Exploring Visual Relationship for Image Captioning"
date: 2018-09-19 07:50:17
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption CNN RNN Relation
author: Ting Yao, Yingwei Pan, Yehao Li, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
It is always well believed that modeling relationships between objects would be helpful for representing and eventually describing an image. Nevertheless, there has not been evidence in support of the idea on image description generation. In this paper, we introduce a new design to explore the connections between objects for image captioning under the umbrella of attention-based encoder-decoder framework. Specifically, we present Graph Convolutional Networks plus Long Short-Term Memory (dubbed as GCN-LSTM) architecture that novelly integrates both semantic and spatial object relationships into image encoder. Technically, we build graphs over the detected objects in an image based on their spatial and semantic connections. The representations of each region proposed on objects are then refined by leveraging graph structure through GCN. With the learnt region-level features, our GCN-LSTM capitalizes on LSTM-based captioning framework with attention mechanism for sentence generation. Extensive experiments are conducted on COCO image captioning dataset, and superior results are reported when comparing to state-of-the-art approaches. More remarkably, GCN-LSTM increases CIDEr-D performance from 120.1% to 128.7% on COCO testing set.

##### Abstract (translated by Google)
人们总是相信，对象之间的建模关系将有助于表示和最终描述图像。然而，没有证据支持关于图像描述生成的想法。在本文中，我们介绍了一种新的设计，用于在基于注意力的编码器 - 解码器框架的保护下探索图像字幕对象之间的连接。具体来说，我们提出了图形卷积网络和长短期记忆（称为GCN-LSTM）架构，它将语义和空间对象关系新颖地集成到图像编码器中。从技术上讲，我们基于它们的空间和语义连接在图像中构建检测到的对象的图形。然后通过GCN利用图形结构来细化在对象上提出的每个区域的表示。借助学习到的区域级功能，我们的GCN-LSTM充分利用基于LSTM的字幕框架以及用于句子生成的注意机制。对COCO图像字幕数据集进行了大量实验，与现有技术方法相比，报告了优异的结果。更值得注意的是，GCN-LSTM在COCO测试装置上将CIDEr-D性能从120.1％提高到128.7％。

##### URL
[http://arxiv.org/abs/1809.07041](http://arxiv.org/abs/1809.07041)

##### PDF
[http://arxiv.org/pdf/1809.07041](http://arxiv.org/pdf/1809.07041)

