---
layout: post
title: "Deep Matching and Validation Network -- An End-to-End Solution to Constrained Image Splicing Localization and Detection"
date: 2017-05-27 05:33:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Yue Wu, Wael AbdAlmageed, Prem Natarajan
mathjax: true
---

* content
{:toc}

##### Abstract
Image splicing is a very common image manipulation technique that is sometimes used for malicious purposes. A splicing detec- tion and localization algorithm usually takes an input image and produces a binary decision indicating whether the input image has been manipulated, and also a segmentation mask that corre- sponds to the spliced region. Most existing splicing detection and localization pipelines suffer from two main shortcomings: 1) they use handcrafted features that are not robust against subsequent processing (e.g., compression), and 2) each stage of the pipeline is usually optimized independently. In this paper we extend the formulation of the underlying splicing problem to consider two input images, a query image and a potential donor image. Here the task is to estimate the probability that the donor image has been used to splice the query image, and obtain the splicing masks for both the query and donor images. We introduce a novel deep convolutional neural network architecture, called Deep Matching and Validation Network (DMVN), which simultaneously localizes and detects image splicing. The proposed approach does not depend on handcrafted features and uses raw input images to create deep learned representations. Furthermore, the DMVN is end-to-end op- timized to produce the probability estimates and the segmentation masks. Our extensive experiments demonstrate that this approach outperforms state-of-the-art splicing detection methods by a large margin in terms of both AUC score and speed.

##### Abstract (translated by Google)
图像拼接是一种非常常见的图像处理技术，有时用于恶意目的。一个拼接检测和定位算法通常需要一个输入图像，并产生一个二元决定，指示输入图像是否已被操纵，以及一个对应拼接区域的分割掩码。大多数现有的拼接检测和定位流水线存在两个主要缺点：1）它们使用对后续处理（例如，压缩）不稳健的手工特征，以及2）通常独立优化流水线的每个阶段。在本文中，我们扩展底层拼接问题的表述，以考虑两个输入图像，一个查询图像和一个潜在的供体图像。这里的任务是估计供体图像被用来拼接查询图像的概率，并获得查询和供体图像的拼接掩码。我们引入一种新的深度卷积神经网络架构，称为深度匹配和验证网络（DMVN），它同时定位和检测图像拼接。所提出的方法不依赖手工特征，并使用原始输入图像来创建深度学习的表示。此外，DMVN被端到端地优化以产生概率估计和分割掩码。我们广泛的实验证明，这种方法在AUC评分和速度方面都优于现有技术的拼接检测方法。

##### URL
[https://arxiv.org/abs/1705.09765](https://arxiv.org/abs/1705.09765)

##### PDF
[https://arxiv.org/pdf/1705.09765](https://arxiv.org/pdf/1705.09765)

