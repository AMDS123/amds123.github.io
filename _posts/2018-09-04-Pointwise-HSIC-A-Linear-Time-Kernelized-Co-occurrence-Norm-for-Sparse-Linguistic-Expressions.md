---
layout: post
title: "Pointwise HSIC: A Linear-Time Kernelized Co-occurrence Norm for Sparse Linguistic Expressions"
date: 2018-09-04 05:33:00
categories: arXiv_CL
tags: arXiv_CL Sparse Embedding RNN
author: Sho Yokoi, Sosuke Kobayashi, Kenji Fukumizu, Jun Suzuki, Kentaro Inui
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new kernel-based co-occurrence measure that can be applied to sparse linguistic expressions (e.g., sentences) with a very short learning time, as an alternative to pointwise mutual information (PMI). As well as deriving PMI from mutual information, we derive this new measure from the Hilbert--Schmidt independence criterion (HSIC); thus, we call the new measure the pointwise HSIC (PHSIC). PHSIC can be interpreted as a smoothed variant of PMI that allows various similarity metrics (e.g., sentence embeddings) to be plugged in as kernels. Moreover, PHSIC can be estimated by simple and fast (linear in the size of the data) matrix calculations regardless of whether we use linear or nonlinear kernels. Empirically, in a dialogue response selection task, PHSIC is learned thousands of times faster than an RNN-based PMI while outperforming PMI in accuracy. In addition, we also demonstrate that PHSIC is beneficial as a criterion of a data selection task for machine translation owing to its ability to give high (low) scores to a consistent (inconsistent) pair with other pairs.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的基于内核的共现度量，它可以应用于学习时间非常短的稀疏语言表达式（例如句子），作为逐点互信息（PMI）的替代方法。除了从互信息中推导出PMI之外，我们还从Hilbert  -  Schmidt独立性准则（HSIC）中推导出这一新指标;因此，我们将新措施称为逐点HSIC（PHSIC）。 PHSIC可以被解释为PMI的平滑变体，其允许将各种相似性度量（例如，句子嵌入）作为内核插入。此外，无论我们使用线性还是非线性内核，都可以通过简单快速（数据大小的线性）矩阵计算来估计PHSIC。根据经验，在对话响应选择任务中，PHSIC的学习速度比基于RNN的PMI快数千倍，同时在准确度上优于PMI。此外，我们还证明了PHSIC作为机器翻译的数据选择任务的标准是有益的，因为它能够为与其他对的一致（不一致）对给出高（低）分数。

##### URL
[http://arxiv.org/abs/1809.00800](http://arxiv.org/abs/1809.00800)

##### PDF
[http://arxiv.org/pdf/1809.00800](http://arxiv.org/pdf/1809.00800)

