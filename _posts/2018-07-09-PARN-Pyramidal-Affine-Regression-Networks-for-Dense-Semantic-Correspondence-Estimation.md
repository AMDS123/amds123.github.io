---
layout: post
title: "PARN: Pyramidal Affine Regression Networks for Dense Semantic Correspondence Estimation"
date: 2018-07-09 04:55:09
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Sangryul Jeon, Seungryong Kim, Dongbo Min, Kwanghoon Sohn
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a deep architecture for dense semantic correspondence, called pyramidal affine regression networks (PARN), that estimates pixel-varying affine transformation fields across images. To deal with intra-class appearance and shape variations that commonly exist among different instances within the same object category, we leverage a pyramidal model where dense affine transformation fields are progressively estimated in a coarse-to-fine manner so that the smoothness constraint is naturally imposed within deep networks. PARN estimates residual affine transformations at each level and composes them to estimate final affine transformations. Furthermore, to overcome the limitations of insufficient training data for semantic correspondence, we propose a novel weakly-supervised training scheme that generates progressive supervisions by leveraging the correspondence consistency across images. Our method is fully learnable in an end-to-end manner and does not require quantizing infinite continuous affine transformation fields. To the best of our knowledge, it is the first work that attempts to estimate dense affine transformation fields in a coarse-to-fine manner within deep networks. Experimental results demonstrate that PARN outperforms the state-of-the-art methods for dense semantic correspondence on various benchmarks.

##### Abstract (translated by Google)
本文提出了一种密集语义对应的深层体系结构，称为金字塔仿射回归网络（PARN），用于估计图像中像素变化的仿射变换域。为了处理同一对象类别中不同实例之间通常存在的类内外观和形状变化，我们利用金字塔模型，其中以粗到细的方式逐步估计密集仿射变换场，使得平滑约束自然强加在深层网络中。 PARN估计每个级别的残差仿射变换并将它们组合以估计最终的仿射变换。此外，为了克服语义对应训练数据不足的局限性，我们提出了一种新颖的弱监督训练方案，通过利用图像间的对应一致性来产生渐进式监督。我们的方法可以以端到端的方式完全学习，并且不需要量化无限连续仿射变换场。据我们所知，这是第一个尝试在深度网络中以粗到细的方式估计密集仿射变换场的工作。实验结果表明，PARN在各种基准测试中优于最先进的密集语义对应方法。

##### URL
[http://arxiv.org/abs/1807.02939](http://arxiv.org/abs/1807.02939)

##### PDF
[http://arxiv.org/pdf/1807.02939](http://arxiv.org/pdf/1807.02939)

