---
layout: post
title: "Built-in Foreground/Background Prior for Weakly-Supervised Semantic Segmentation"
date: 2016-09-02 01:49:51
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Fatemehsadat Saleh, Mohammad Sadegh Ali Akbarian, Mathieu Salzmann, Lars Petersson, Stephen Gould, Jose M. Alvarez
mathjax: true
---

* content
{:toc}

##### Abstract
Pixel-level annotations are expensive and time consuming to obtain. Hence, weak supervision using only image tags could have a significant impact in semantic segmentation. Recently, CNN-based methods have proposed to fine-tune pre-trained networks using image tags. Without additional information, this leads to poor localization accuracy. This problem, however, was alleviated by making use of objectness priors to generate foreground/background masks. Unfortunately these priors either require training pixel-level annotations/bounding boxes, or still yield inaccurate object boundaries. Here, we propose a novel method to extract markedly more accurate masks from the pre-trained network itself, forgoing external objectness modules. This is accomplished using the activations of the higher-level convolutional layers, smoothed by a dense CRF. We demonstrate that our method, based on these masks and a weakly-supervised loss, outperforms the state-of-the-art tag-based weakly-supervised semantic segmentation techniques. Furthermore, we introduce a new form of inexpensive weak supervision yielding an additional accuracy boost.

##### Abstract (translated by Google)
像素级注释是昂贵且耗时的。因此，只使用图像标签的弱监督可能会对语义分割产生重大影响。近来，基于CNN的方法已经提出使用图像标签来微调预先训练的网络。没有额外的信息，这导致了很差的定位精度。然而，这个问题通过使用对象先验来生成前景/背景掩模而得到缓解。不幸的是，这些先验要么需要训练像素级别的注释/边界框，要么仍然会产生不准确的对象边界。在这里，我们提出了一种新的方法，从预先训练的网络本身提取明显更准确的掩码，放弃外部对象模块。这是通过使用高密度CRF平滑的更高级卷积层的激活来实现的。我们证明，基于这些掩码和弱监督损失的我们的方法胜过了最先进的基于标签的弱监督语义分割技术。此外，我们引入了一种廉价的弱监督的新形式，产生额外的准确度提升。

##### URL
[https://arxiv.org/abs/1609.00446](https://arxiv.org/abs/1609.00446)

##### PDF
[https://arxiv.org/pdf/1609.00446](https://arxiv.org/pdf/1609.00446)

