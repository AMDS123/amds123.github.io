---
layout: post
title: "Segmentation from Natural Language Expressions"
date: 2016-03-20 04:10:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation RNN
author: Ronghang Hu, Marcus Rohrbach, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we approach the novel problem of segmenting an image based on a natural language expression. This is different from traditional semantic segmentation over a predefined set of semantic classes, as e.g., the phrase "two men sitting on the right bench" requires segmenting only the two people on the right bench and no one standing or sitting on another bench. Previous approaches suitable for this task were limited to a fixed set of categories and/or rectangular regions. To produce pixelwise segmentation for the language expression, we propose an end-to-end trainable recurrent and convolutional network model that jointly learns to process visual and linguistic information. In our model, a recurrent LSTM network is used to encode the referential expression into a vector representation, and a fully convolutional network is used to a extract a spatial feature map from the image and output a spatial response map for the target object. We demonstrate on a benchmark dataset that our model can produce quality segmentation output from the natural language expression, and outperforms baseline methods by a large margin.

##### Abstract (translated by Google)
在本文中，我们接近基于自然语言表达的分割图像的新颖问题。这与预定义的一组语义类别上的传统语义分割不同，例如，“坐在正确长凳上的两名男子”这一短语只需要将正确的长凳上的两个人分开，并且没有人站在或坐在另一个长凳上。先前适用于此任务的方法仅限于一组固定类别和/或矩形区域。为了产生语言表达式的像素分割，我们提出了一个端到端的可训练循环和卷积网络模型，共同学习处理视觉和语言信息。在我们的模型中，使用经常性的LSTM网络将参考表达式编码为矢量表示，并且使用完全卷积网络从图像中提取空间特征图并输出目标对象的空间响应图。我们在基准数据集上演示，我们的模型可以从自然语言表达式生成质量分割输出，并且大大超过了基线方法。

##### URL
[https://arxiv.org/abs/1603.06180](https://arxiv.org/abs/1603.06180)

##### PDF
[https://arxiv.org/pdf/1603.06180](https://arxiv.org/pdf/1603.06180)

