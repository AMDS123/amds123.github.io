---
layout: post
title: "Optimization of the Jaccard index for image segmentation with the Lovász hinge"
date: 2017-05-24 14:33:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Optimization Deep_Learning
author: Maxim Berman, Matthew B. Blaschko
mathjax: true
---

* content
{:toc}

##### Abstract
The Jaccard loss, commonly referred to as the intersection-over-union loss, is commonly employed in the evaluation of segmentation quality due to its better perceptual quality and scale invariance, which lends appropriate relevance to small objects compared with per-pixel losses. We present a method for direct optimization of the per-image intersection-over-union loss in neural networks, in the context of semantic image segmentation, based on a convex surrogate: the Lov\'asz hinge. The loss is shown to perform better with respect to the Jaccard index measure than other losses traditionally used in the context of semantic segmentation; such as cross-entropy. We develop a specialized optimization method, based on an efficient computation of the proximal operator of the Lov\'asz hinge, yielding reliably faster and more stable optimization than alternatives. We demonstrate the effectiveness of the method by showing substantially improved intersection-overunion segmentation scores on the Pascal VOC dataset using a state-of-the-art deep learning segmentation architecture.

##### Abstract (translated by Google)
Jaccard损失通常被称为交叉口联合损失，由于其更好的感知质量和尺度不变性，通常被用于评估分割质量，与每像素损失相比，这对于小物体具有适当的相关性。在语义图像分割的背景下，我们提出了一种基于凸代理：Lov \'asz铰链的直接优化神经网络中的每图像相交跨越损失的方法。在Jaccard指数测度方面，损失显示出比传统上在语义分割中使用的其他损失更好;如交叉熵。我们开发了一种专门的优化方法，基于Lov \'asz铰链近端算子的有效计算，可以产生比替代方案更快，更稳定的优化。我们通过使用最先进的深度学习分割体系结构来显示Pascal VOC数据集中的交叉连接分割分数的显着改善来证明该方法的有效性。

##### URL
[https://arxiv.org/abs/1705.08790](https://arxiv.org/abs/1705.08790)

##### PDF
[https://arxiv.org/pdf/1705.08790](https://arxiv.org/pdf/1705.08790)

