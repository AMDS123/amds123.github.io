---
layout: post
title: "Improved Style Transfer by Respecting Inter-layer Correlations"
date: 2018-01-05 22:41:11
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Relation
author: Mao-Chuang Yeh, Shuai Tang
mathjax: true
---

* content
{:toc}

##### Abstract
A popular series of style transfer methods apply a style to a content image by controlling mean and covariance of values in early layers of a feature stack. This is insufficient for transferring styles that have strong structure across spatial scales like, e.g., textures where dots lie on long curves. This paper demonstrates that controlling inter-layer correlations yields visible improvements in style transfer methods. We achieve this control by computing cross-layer, rather than within-layer, gram matrices. We find that (a) cross-layer gram matrices are sufficient to control within-layer statistics. Inter-layer correlations improves style transfer and texture synthesis. The paper shows numerous examples on "hard" real style transfer problems (e.g. long scale and hierarchical patterns); (b) a fast approximate style transfer method can control cross-layer gram matrices; (c) we demonstrate that multiplicative, rather than additive style and content loss, results in very good style transfer. Multiplicative loss produces a visible emphasis on boundaries, and means that one hyper-parameter can be eliminated.

##### Abstract (translated by Google)
流行的一系列样式转换方法通过控制特征堆栈的早期层中的值的均值和协方差将样式应用于内容图像。这不足以转移在空间尺度上具有强结构的样式，例如，点位于长曲线上的纹理。本文表明，控制层间相关性可以显着改善样式转换方法。我们通过计算跨层而不是层内克矩阵来实现这种控制。我们发现（a）跨层克矩阵足以控制层内统计。层间关联改善了样式转换和纹理合成。本文展示了许多关于“硬”真实风格转移问题（例如，长期规模和分层模式）的例子; （b）快速近似样式转换方法可以控制跨层克矩阵; （三）我们证明，乘法，而不是添加剂的风格和内容的损失，导致非常好的风格转移。乘法损失对边界产生可见的重点，意味着可以消除一个超参数。

##### URL
[http://arxiv.org/abs/1801.01933](http://arxiv.org/abs/1801.01933)

##### PDF
[http://arxiv.org/pdf/1801.01933](http://arxiv.org/pdf/1801.01933)

