---
layout: post
title: "Spatially Localized Atlas Network Tiles Enables 3D Whole Brain Segmentation from Limited Data"
date: 2018-06-01 21:39:47
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Yuankai Huo, Zhoubing Xu, Katherine Aboud, Prasanna Parvathaneni, Shunxing Bao, Camilo Bermudez, Susan M. Resnick, Laurie E. Cutting, Bennett A. Landman
mathjax: true
---

* content
{:toc}

##### Abstract
Whole brain segmentation on a structural magnetic resonance imaging (MRI) is essential in non-invasive investigation for neuroanatomy. Historically, multi-atlas segmentation (MAS) has been regarded as the de facto standard method for whole brain segmentation. Recently, deep neural network approaches have been applied to whole brain segmentation by learning random patches or 2D slices. Yet, few previous efforts have been made on detailed whole brain segmentation using 3D networks due to the following challenges: (1) fitting entire whole brain volume into 3D networks is restricted by the current GPU memory, and (2) the large number of targeting labels (e.g., &gt; 100 labels) with limited number of training 3D volumes (e.g., &lt; 50 scans). In this paper, we propose the spatially localized atlas network tiles (SLANT) method to distribute multiple independent 3D fully convolutional networks to cover overlapped sub-spaces in a standard atlas space. This strategy simplifies the whole brain learning task to localized sub-tasks, which was enabled by combing canonical registration and label fusion techniques with deep learning. To address the second challenge, auxiliary labels on 5111 initially unlabeled scans were created by MAS for pre-training. From empirical validation, the state-of-the-art MAS method achieved mean Dice value of 0.76, 0.71, and 0.68, while the proposed method achieved 0.78, 0.73, and 0.71 on three validation cohorts. Moreover, the computational time reduced from &gt; 30 hours using MAS to ~15 minutes using the proposed method. The source code is available online https://github.com/MASILab/SLANT_train_seg

##### Abstract (translated by Google)
对结构性磁共振成像（MRI）进行全脑分割对于神经解剖学的非侵入性研究至关重要。历史上，多图集分割（MAS）被认为是全脑分割的事实标准方法。最近，深度神经网络方法已经通过学习随机斑块或2D切片应用于全脑分割。然而，由于以下挑战，之前很少有人使用3D网络对详细的全脑分割做出了努力：（1）将整个大脑体积拟合到3D网络中受到当前GPU存储器的限制，以及（2）大量目标具有有限数量的训练3D体积（例如，<50次扫描）的标签（例如，> 100个标签）。在本文中，我们提出了空间局部图谱网格（SLANT）方法来分布多个独立的3D完全卷积网络来覆盖标准阿特拉斯空间中的重叠子空间。该策略将整个大脑学习任务简化为本地化的子任务，这通过将规范注册和标签融合技术与深度学习相结合而得以实现。为解决第二个挑战，5111初始未标记扫描的辅助标签由MAS创建用于预培训。从经验验证中，最先进的MAS方法实现了0.76,0.71和0.68的平均Dice值，而所提出的方法在三个验证群组中达到0.78,0.73和0.71。而且，计算时间从＆gt;使用所提出的方法使用MAS约30小时〜15分钟。源代码可在线获取https://github.com/MASILab/SLANT_train_seg

##### URL
[http://arxiv.org/abs/1806.00546](http://arxiv.org/abs/1806.00546)

##### PDF
[http://arxiv.org/pdf/1806.00546](http://arxiv.org/pdf/1806.00546)

