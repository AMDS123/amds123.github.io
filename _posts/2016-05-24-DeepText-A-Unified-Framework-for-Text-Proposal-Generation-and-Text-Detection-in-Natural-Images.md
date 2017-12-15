---
layout: post
title: "DeepText: A Unified Framework for Text Proposal Generation and Text Detection in Natural Images"
date: 2016-05-24 06:48:23
categories: arXiv_CV
tags: arXiv_CV Text_Classification CNN Classification Detection
author: Zhuoyao Zhong, Lianwen Jin, Shuye Zhang, Ziyong Feng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop a novel unified framework called DeepText for text region proposal generation and text detection in natural images via a fully convolutional neural network (CNN). First, we propose the inception region proposal network (Inception-RPN) and design a set of text characteristic prior bounding boxes to achieve high word recall with only hundred level candidate proposals. Next, we present a powerful textdetection network that embeds ambiguous text category (ATC) information and multilevel region-of-interest pooling (MLRP) for text and non-text classification and accurate localization. Finally, we apply an iterative bounding box voting scheme to pursue high recall in a complementary manner and introduce a filtering algorithm to retain the most suitable bounding box, while removing redundant inner and outer boxes for each text instance. Our approach achieves an F-measure of 0.83 and 0.85 on the ICDAR 2011 and 2013 robust text detection benchmarks, outperforming previous state-of-the-art results.

##### Abstract (translated by Google)
在本文中，我们通过完全卷积神经网络（CNN）开发了一个名为DeepText的新的统一框架，用于文本区域提案生成和自然图像中的文本检测。首先提出了初始区域提议网络（Inception-RPN），并设计了一套文本特征先验边界框，实现了高级词汇回忆，仅有百个级别的候选方案。接下来，我们提出了一个强大的文本检测网络，嵌入了文本和非文本分类和准确定位的模糊文本类别（ATC）信息和多层次感兴趣区域（MLRP）。最后，我们应用迭代边界框投票方案来追求高回忆率，并引入一个滤波算法来保留最合适的边界框，同时去除每个文本实例的冗余内外框。我们的方法在ICDAR 2011和2013强健文本检测基准上实现了0.83和0.85的F-measure，超越了以前的最新成果。

##### URL
[https://arxiv.org/abs/1605.07314](https://arxiv.org/abs/1605.07314)

##### PDF
[https://arxiv.org/pdf/1605.07314](https://arxiv.org/pdf/1605.07314)

