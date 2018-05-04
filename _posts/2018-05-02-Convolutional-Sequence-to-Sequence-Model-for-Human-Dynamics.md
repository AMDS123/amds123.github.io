---
layout: post
title: "Convolutional Sequence to Sequence Model for Human Dynamics"
date: 2018-05-02 07:42:04
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Relation
author: Chen Li, Zhen Zhang, Wee Sun Lee, Gim Hee Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Human motion modeling is a classic problem in computer vision and graphics. Challenges in modeling human motion include high dimensional prediction as well as extremely complicated dynamics.We present a novel approach to human motion modeling based on convolutional neural networks (CNN). The hierarchical structure of CNN makes it capable of capturing both spatial and temporal correlations effectively. In our proposed approach,a convolutional long-term encoder is used to encode the whole given motion sequence into a long-term hidden variable, which is used with a decoder to predict the remainder of the sequence. The decoder itself also has an encoder-decoder structure, in which the short-term encoder encodes a shorter sequence to a short-term hidden variable, and the spatial decoder maps the long and short-term hidden variable to motion predictions. By using such a model, we are able to capture both invariant and dynamic information of human motion, which results in more accurate predictions. Experiments show that our algorithm outperforms the state-of-the-art methods on the Human3.6M and CMU Motion Capture datasets. Our code is available at the project website.

##### Abstract (translated by Google)
人体运动建模是计算机视觉和图形中的经典问题。人体运动建模的挑战包括高维预测以及极其复杂的动力学。我们提出了一种基于卷积神经网络（CNN）的人体运动建模新方法。 CNN的层次结构使其能够有效地捕获空间和时间相关性。在我们提出的方法中，使用卷积长期编码器将整个给定的运动序列编码成长期隐藏变量，其与解码器一起用于预测序列的剩余部分。解码器本身也具有编码器 - 解码器结构，其中短期编码器将较短序列编码为短期隐藏变量，并且空间解码器将长期和短期隐藏变量映射到运动预测。通过使用这样的模型，我们能够捕获人体运动的不变信息和动态信息，从而获得更准确的预测结果。实验表明，我们的算法优于Human3.6M和CMU Motion Capture数据集上的最新方法。我们的代码可在项目网站上找到。

##### URL
[https://arxiv.org/abs/1805.00655](https://arxiv.org/abs/1805.00655)

##### PDF
[https://arxiv.org/pdf/1805.00655](https://arxiv.org/pdf/1805.00655)

