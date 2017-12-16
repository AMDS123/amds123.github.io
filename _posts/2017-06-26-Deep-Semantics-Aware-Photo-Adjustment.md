---
layout: post
title: "Deep Semantics-Aware Photo Adjustment"
date: 2017-06-26 07:35:07
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Seonghyeon Nam, Seon Joo Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic photo adjustment is to mimic the photo retouching style of professional photographers and automatically adjust photos to the learned style. There have been many attempts to model the tone and the color adjustment globally with low-level color statistics. Also, spatially varying photo adjustment methods have been studied by exploiting high-level features and semantic label maps. Those methods are semantics-aware since the color mapping is dependent on the high-level semantic context. However, their performance is limited to the pre-computed hand-crafted features and it is hard to reflect user's preference to the adjustment. In this paper, we propose a deep neural network that models the semantics-aware photo adjustment. The proposed network exploits bilinear models that are the multiplicative interaction of the color and the contexual features. As the contextual features we propose the semantic adjustment map, which discovers the inherent photo retouching presets that are applied according to the scene context. The proposed method is trained using a robust loss with a scene parsing task. The experimental results show that the proposed method outperforms the existing method both quantitatively and qualitatively. The proposed method also provides users a way to retouch the photo by their own likings by giving customized adjustment maps.

##### Abstract (translated by Google)
自动照片调整是模仿专业摄影师的照片润饰风格，并自动调整照片的学习风格。已经有许多尝试用低级色彩统计来模拟全局色调和色彩调整。此外，通过利用高级特征和语义标签图，已经研究了空间变化的照片调整方法。由于颜色映射依赖于高级语义上下文，所以这些方法是语义感知的。然而，他们的表现仅限于预先计算的手工特征，很难反映用户对调整的偏好。在本文中，我们提出了一个深度神经网络模型的语义意识的照片调整。所提出的网络利用了双线性模型，这些模型是颜色和特征的倍增交互作用。作为上下文特征，我们提出了语义调整映射，该映射发现了根据场景上下文应用的固有的照片修饰预设。所提出的方法是在场景解析任务中使用强健的损失进行训练的。实验结果表明，所提出的方法在数量和质量上均优于现有方法。所提出的方法还为用户提供了一种通过给定制的调整图来根据自己的喜好润饰照片的方法。

##### URL
[https://arxiv.org/abs/1706.08260](https://arxiv.org/abs/1706.08260)

##### PDF
[https://arxiv.org/pdf/1706.08260](https://arxiv.org/pdf/1706.08260)

