---
layout: post
title: "Deep Learning from Label Proportions for Emphysema Quantification"
date: 2018-07-23 13:34:01
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Deep_Learning
author: Gerda Bortsova, Florian Dubost, Silas &#xd8;rting, Ioannis Katramados, Laurens Hogeweg, Laura Thomsen, Mathilde Wille, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end deep learning method that learns to estimate emphysema extent from proportions of the diseased tissue. These proportions were visually estimated by experts using a standard grading system, in which grades correspond to intervals (label example: 1-5% of diseased tissue). The proposed architecture encodes the knowledge that the labels represent a volumetric proportion. A custom loss is designed to learn with intervals. Thus, during training, our network learns to segment the diseased tissue such that its proportions fit the ground truth intervals. Our architecture and loss combined improve the performance substantially (8% ICC) compared to a more conventional regression network. We outperform traditional lung densitometry and two recently published methods for emphysema quantification by a large margin (at least 7% AUC and 15% ICC), and achieve near-human-level performance. Moreover, our method generates emphysema segmentations that predict the spatial distribution of emphysema at human level.

##### Abstract (translated by Google)
我们提出了一种端到端的深度学习方法，该方法学习根据患病组织的比例来估计肺气肿的程度。专家使用标准分级系统在视觉上估计这些比例，其中等级对应于间隔（标签实例：1-5％的患病组织）。建议的体系结构编码标签代表体积比例的知识。自定义损失旨在通过间隔学习。因此，在训练期间，我们的网络学会分割患病组织，使其比例适合地面真实间隔。与更传统的回归网络相比，我们的架构和损耗相结合，大大提高了性能（8％ICC）。我们的表现优于传统的肺密度测定法和最近发表的两种肺气肿量化方法（至少7％AUC和15％ICC），并达到近乎人类的表现。此外，我们的方法产生肺气肿分割，预测人类肺气肿的空间分布。

##### URL
[http://arxiv.org/abs/1807.08601](http://arxiv.org/abs/1807.08601)

##### PDF
[http://arxiv.org/pdf/1807.08601](http://arxiv.org/pdf/1807.08601)

