---
layout: post
title: "Reformulating Level Sets as Deep Recurrent Neural Network Approach to Semantic Segmentation"
date: 2017-04-12 01:51:52
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Deep_Learning
author: Ngan Le, Kha Gia Quach, Khoa Luu, Marios Savvides, Chenchen Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Variational Level Set (LS) has been a widely used method in medical segmentation. However, it is limited when dealing with multi-instance objects in the real world. In addition, its segmentation results are quite sensitive to initial settings and highly depend on the number of iterations. To address these issues and boost the classic variational LS methods to a new level of the learnable deep learning approaches, we propose a novel definition of contour evolution named Recurrent Level Set (RLS)} to employ Gated Recurrent Unit under the energy minimization of a variational LS functional. The curve deformation process in RLS is formed as a hidden state evolution procedure and updated by minimizing an energy functional composed of fitting forces and contour length. By sharing the convolutional features in a fully end-to-end trainable framework, we extend RLS to Contextual RLS (CRLS) to address semantic segmentation in the wild. The experimental results have shown that our proposed RLS improves both computational time and segmentation accuracy against the classic variations LS-based method, whereas the fully end-to-end system CRLS achieves competitive performance compared to the state-of-the-art semantic segmentation approaches.

##### Abstract (translated by Google)
变分水平集（LS）在医学分割中被广泛使用。但是，在现实世界中处理多实例对象时是有限的。另外，其分割结果对初始设置非常敏感，并且高度依赖于迭代次数。为了解决这些问题，并将经典变分LS方法提升到可学习的深度学习方法的新水平，我们提出了一个新的轮廓演化的定义，称为循环水平集（RLS）}，以在变分能量最小化LS功能。 RLS中的曲线变形过程形成隐形状态演化过程，并通过最小化由拟合力和轮廓长度组成的能量函数来更新。通过在完全端到端的可训练框架中共享卷积特征，我们将RLS扩展到上下文RLS（CRLS）以解决野外语义分割问题。实验结果表明，我们提出的RLS改善了计算时间和分割准确性与经典变化基于LS的方法，而完全端到端的系统CRLS实现了竞争性能相比，最先进的语义分割方法。

##### URL
[https://arxiv.org/abs/1704.03593](https://arxiv.org/abs/1704.03593)

##### PDF
[https://arxiv.org/pdf/1704.03593](https://arxiv.org/pdf/1704.03593)

