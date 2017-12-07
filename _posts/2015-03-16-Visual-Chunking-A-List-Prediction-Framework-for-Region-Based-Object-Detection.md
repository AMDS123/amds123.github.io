---
layout: post
title: "Visual Chunking: A List Prediction Framework for Region-Based Object Detection"
date: 2015-03-16 21:20:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Nicholas Rhinehart, Jiaji Zhou, Martial Hebert, J. Andrew Bagnell
mathjax: true
---

* content
{:toc}

##### Abstract
We consider detecting objects in an image by iteratively selecting from a set of arbitrarily shaped candidate regions. Our generic approach, which we term visual chunking, reasons about the locations of multiple object instances in an image while expressively describing object boundaries. We design an optimization criterion for measuring the performance of a list of such detections as a natural extension to a common per-instance metric. We present an efficient algorithm with provable performance for building a high-quality list of detections from any candidate set of region-based proposals. We also develop a simple class-specific algorithm to generate a candidate region instance in near-linear time in the number of low-level superpixels that outperforms other region generating methods. In order to make predictions on novel images at testing time without access to ground truth, we develop learning approaches to emulate these algorithms' behaviors. We demonstrate that our new approach outperforms sophisticated baselines on benchmark datasets.

##### Abstract (translated by Google)
我们考虑通过从一组任意形状的候选区域迭代选择来检测图像中的对象。我们称之为视觉分块的通用方法是在图像中描述多个对象实例的位置，同时明确描述对象的边界。我们设计了一个优化标准，用于衡量一个这样的检测列表的性能，作为一个常见的每个实例度量的自然扩展。我们提出了一个有效的算法与可证明的性能，从任何候选集合的基于区域的提案构建高质量的检测列表。我们还开发了一个简单的类特定算法来生成一个近似线性时间的候选区域实例，其数量超过了其他区域生成方法的低级超像素。为了在测试时间对新图像进行预测而不需要了解真实情况，我们开发学习方法来模拟这些算法的行为。我们证明了我们的新方法胜过了基准数据集上复杂的基线。

##### URL
[https://arxiv.org/abs/1410.7376](https://arxiv.org/abs/1410.7376)

##### PDF
[https://arxiv.org/pdf/1410.7376](https://arxiv.org/pdf/1410.7376)

