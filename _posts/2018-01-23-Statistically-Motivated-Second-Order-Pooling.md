---
layout: post
title: "Statistically Motivated Second Order Pooling"
date: 2018-01-23 11:39:19
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Kaicheng Yu, Mathieu Salzmann
mathjax: true
---

* content
{:toc}

##### Abstract
Second-order pooling, a.k.a. bilinear pooling, has proven effective for visual recognition. The recent progress in this area has focused on either designing normalization techniques for second-order models, or compressing the second-order representations. However, these two directions have typically been followed separately, and without any clear statistical motivation. Here, by contrast, we introduce a statistically-motivated framework that jointly tackles normalization and compression of second-order representations. To this end, we design a parametric vectorization layer, which maps a covariance matrix, known to follow a Wishart distribution, to a vector whose elements can be shown to follow a Chi-square distribution. We then propose to make use of a square-root normalization, which makes the distribution of the resulting representation converge to a Gaussian, thus complying with the standard machine learning assumption. As evidenced by our experiments, this lets us outperform the state-of-the-art second-order models on several benchmark recognition datasets.

##### Abstract (translated by Google)
二阶汇集，又名双线性汇集，已经证明对于视觉识别是有效的。最近在这方面的进展集中在为二阶模型设计归一化技术或压缩二阶表示。但是，这两个方向通常是分开的，没有明确的统计动机。在这里，相比之下，我们引入了一个统计学动机的框架，共同解决二阶表示的归一化和压缩。为此，我们设计了一个参数向量化层，它将一个已知遵循Wishart分布的协方差矩阵映射到一个向量，其元素可以表示为卡方分布。然后我们提出使用平方根归一化，这使得结果表示的分布收敛到高斯，从而符合标准的机器学习假设。正如我们的实验所证明的那样，这使我们在几个基准识别数据集上的性能超越了最先进的二阶模型。

##### URL
[http://arxiv.org/abs/1801.07492](http://arxiv.org/abs/1801.07492)

##### PDF
[http://arxiv.org/pdf/1801.07492](http://arxiv.org/pdf/1801.07492)

