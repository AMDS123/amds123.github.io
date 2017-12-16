---
layout: post
title: "Incorporating Network Built-in Priors in Weakly-supervised Semantic Segmentation"
date: 2017-06-06 03:23:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Recognition
author: Fatemeh Sadat Saleh, Mohammad Sadegh Aliakbarian, Mathieu Salzmann, Lars Petersson, Jose M. Alvarez, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
Pixel-level annotations are expensive and time consuming to obtain. Hence, weak supervision using only image tags could have a significant impact in semantic segmentation. Recently, CNN-based methods have proposed to fine-tune pre-trained networks using image tags. Without additional information, this leads to poor localization accuracy. This problem, however, was alleviated by making use of objectness priors to generate foreground/background masks. Unfortunately these priors either require pixel-level annotations/bounding boxes, or still yield inaccurate object boundaries. Here, we propose a novel method to extract accurate masks from networks pre-trained for the task of object recognition, thus forgoing external objectness modules. We first show how foreground/background masks can be obtained from the activations of higher-level convolutional layers of a network. We then show how to obtain multi-class masks by the fusion of foreground/background ones with information extracted from a weakly-supervised localization network. Our experiments evidence that exploiting these masks in conjunction with a weakly-supervised training loss yields state-of-the-art tag-based weakly-supervised semantic segmentation results.

##### Abstract (translated by Google)
像素级注释是昂贵且耗时的。因此，只使用图像标签的弱监督可能会对语义分割产生重大影响。近来，基于CNN的方法已经提出使用图像标签来微调预先训练的网络。没有额外的信息，这导致了很差的定位精度。然而，这个问题通过使用对象先验来生成前景/背景掩模而得到缓解。不幸的是，这些先验要么需要像素级别的注释/边界框，要么仍然会产生不准确的对象边界。在这里，我们提出了一种新的方法来提取准确的掩模从网络预先训练的对象识别任务，从而放弃外部对象模块。我们首先展示如何从网络的更高级卷积层的激活中获得前景/背景掩模。然后，我们展示了如何通过前景/背景融合和弱监督定位网络提取的信息来获得多类掩模。我们的实验证明，利用这些掩码结合弱监督的训练损失，可以得到最先进的基于标签的弱监督语义分割结果。

##### URL
[https://arxiv.org/abs/1706.02189](https://arxiv.org/abs/1706.02189)

##### PDF
[https://arxiv.org/pdf/1706.02189](https://arxiv.org/pdf/1706.02189)

