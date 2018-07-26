---
layout: post
title: "Repeatability Is Not Enough: Learning Affine Regions via Discriminability"
date: 2018-07-25 15:16:50
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Dmytro Mishkin, Filip Radenovic, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
A method for learning local affine-covariant regions is presented. We show that maximizing geometric repeatability does not lead to local regions, a.k.a features,that are reliably matched and this necessitates descriptor-based learning. We explore factors that influence such learning and registration: the loss function, descriptor type, geometric parametrization and the trade-off between matchability and geometric accuracy and propose a novel hard negative-constant loss function for learning of affine regions. The affine shape estimator -- AffNet -- trained with the hard negative-constant loss outperforms the state-of-the-art in bag-of-words image retrieval and wide baseline stereo. The proposed training process does not require precisely geometrically aligned patches.The source codes and trained weights are available at https://github.com/ducha-aiki/affnet

##### Abstract (translated by Google)
提出了一种用于学习局部仿射协变区域的方法。我们表明，最大化几何可重复性不会导致局部区域，即a.k.a特征，这些特征可靠地匹配，这就需要基于描述符的学习。我们探讨了影响这种学习和注册的因素：损失函数，描述符类型，几何参数化以及匹配性和几何精度之间的权衡，并提出了一种新的硬负 - 常数损失函数来学习仿射区域。仿射形状估算器 -  AffNet--用硬负恒定损失训练，优于最先进的词袋图像检索和宽基线立体声。建议的培训过程不需要精确几何对齐的补丁。源代码和训练过的权重可在https://github.com/ducha-aiki/affnet获得。

##### URL
[http://arxiv.org/abs/1711.06704](http://arxiv.org/abs/1711.06704)

##### PDF
[http://arxiv.org/pdf/1711.06704](http://arxiv.org/pdf/1711.06704)

