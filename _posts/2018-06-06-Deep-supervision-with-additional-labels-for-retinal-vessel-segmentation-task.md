---
layout: post
title: "Deep supervision with additional labels for retinal vessel segmentation task"
date: 2018-06-06 11:41:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Yishuo Zhang, Albert C.S. Chung
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic analysis of retinal blood images is of vital importance in diagnosis tasks of retinopathy. Segmenting vessels accurately is a fundamental step in analysing retinal images. However, it is usually difficult due to various imaging conditions, low image contrast and the appearance of pathologies such as micro-aneurysms. In this paper, we propose a novel method with deep neural networks to solve this problem. We utilize U-net with residual connection to detect vessels. To achieve better accuracy, we introduce an edge-aware mechanism, in which we convert the original task into a multi-class task by adding additional labels on boundary areas. In this way, the network will pay more attention to the boundary areas of vessels and achieve a better performance, especially in tiny vessels detecting. Besides, side output layers are applied in order to give deep supervision and therefore help convergence. We train and evaluate our model on three databases: DRIVE, STARE, and CHASEDB1. Experimental results show that our method has a comparable performance with AUC of 97.99% on DRIVE and an efficient running time compared to the state-of-the-art methods.

##### Abstract (translated by Google)
自动分析视网膜血液图像对于视网膜病变的诊断任务至关重要。准确分割血管是分析视网膜图像的基本步骤。然而，由于各种成像条件，低图像对比度以及诸如微动脉瘤等病变的出现，通常是困难的。在本文中，我们提出了一种新的深度神经网络方法来解决这个问题。我们利用剩余连接的U-Net来检测船只。为了获得更好的准确性，我们引入了边缘感知机制，其中我们通过在边界区域添加附加标签将原始任务转换为多任务任务。这样，网络将更加关注船舶的边界区域，并取得更好的性能，特别是在小型船舶检测中。此外，侧面输出层的应用是为了给予深度监督，因此有助于收敛。我们在三个数据库上训练和评估我们的模型：DRIVE，STARE和CHASEDB1。实验结果表明，我们的方法具有与DRIVE上的97.99％的AUC相当的性能以及与最先进的方法相比有效的运行时间。

##### URL
[http://arxiv.org/abs/1806.02132](http://arxiv.org/abs/1806.02132)

##### PDF
[http://arxiv.org/pdf/1806.02132](http://arxiv.org/pdf/1806.02132)

