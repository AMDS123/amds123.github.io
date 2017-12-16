---
layout: post
title: "Deep Structured Learning for Facial Action Unit Intensity Estimation"
date: 2017-04-14 16:51:40
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Robert Walecki, Ognjen (Oggi)Rudovic, Vladimir Pavlovic, Björn Schuller, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of automated estimation of facial expression intensity. This involves estimation of multiple output variables (facial action units --- AUs) that are structurally dependent. Their structure arises from statistically induced co-occurrence patterns of AU intensity levels. Modeling this structure is critical for improving the estimation performance; however, this performance is bounded by the quality of the input features extracted from face images. The goal of this paper is to model these structures and estimate complex feature representations simultaneously by combining conditional random field (CRF) encoded AU dependencies with deep learning. To this end, we propose a novel Copula CNN deep learning approach for modeling multivariate ordinal variables. Our model accounts for $ordinal$ structure in output variables and their $non$-$linear$ dependencies via copula functions modeled as cliques of a CRF. These are jointly optimized with deep CNN feature encoding layers using a newly introduced balanced batch iterative training algorithm. We demonstrate the effectiveness of our approach on the task of AU intensity estimation on two benchmark datasets. We show that joint learning of the deep features and the target output structure results in significant performance gains compared to existing deep structured models for analysis of facial expressions.

##### Abstract (translated by Google)
我们考虑自动估计面部表情强度的任务。这涉及多个输出变量（面部动作单位--- AU）的结构依赖性的估计。它们的结构来自AU强度水平的统计诱导的共现模式。对这种结构进行建模对于提高估计性能至关重要;然而，这种表现受到从面部图像提取的输入特征的质量的限制。本文的目标是通过将条件随机场（CRF）编码的AU依赖与深度学习相结合来对这些结构进行建模并同时估计复杂特征表示。为此，我们提出了一种新的Copula CNN深度学习方法来建模多元序数变量。我们的模型在输出变量中考虑$ ordinal $结构，并通过作为CRF派系的copula函数来解释$ non $  -  $ linear $依赖关系。通过使用新引入的平衡批量迭代训练算法，对CNN特征编码层进行深度优化。我们证明了我们的方法在两个基准数据集上的非盟强度估计任务的有效性。我们表明，深层特征和目标输出结构的联合学习与现有的面部表情分析的深层结构模型相比，会带来显着的性能提升。

##### URL
[https://arxiv.org/abs/1704.04481](https://arxiv.org/abs/1704.04481)

##### PDF
[https://arxiv.org/pdf/1704.04481](https://arxiv.org/pdf/1704.04481)

