---
layout: post
title: "Unsupervised Category Discovery via Looped Deep Pseudo-Task Optimization Using a Large Scale Radiology Image Database"
date: 2016-03-25 17:16:00
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification Quantitative Recognition
author: Xiaosong Wang, Le Lu, Hoo-chang Shin, Lauren Kim, Isabella Nogues, Jianhua Yao, Ronald Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Obtaining semantic labels on a large scale radiology image database (215,786 key images from 61,845 unique patients) is a prerequisite yet bottleneck to train highly effective deep convolutional neural network (CNN) models for image recognition. Nevertheless, conventional methods for collecting image labels (e.g., Google search followed by crowd-sourcing) are not applicable due to the formidable difficulties of medical annotation tasks for those who are not clinically trained. This type of image labeling task remains non-trivial even for radiologists due to uncertainty and possible drastic inter-observer variation or inconsistency. In this paper, we present a looped deep pseudo-task optimization procedure for automatic category discovery of visually coherent and clinically semantic (concept) clusters. Our system can be initialized by domain-specific (CNN trained on radiology images and text report derived labels) or generic (ImageNet based) CNN models. Afterwards, a sequence of pseudo-tasks are exploited by the looped deep image feature clustering (to refine image labels) and deep CNN training/classification using new labels (to obtain more task representative deep features). Our method is conceptually simple and based on the hypothesized "convergence" of better labels leading to better trained CNN models which in turn feed more effective deep image features to facilitate more meaningful clustering/labels. We have empirically validated the convergence and demonstrated promising quantitative and qualitative results. Category labels of significantly higher quality than those in previous work are discovered. This allows for further investigation of the hierarchical semantic nature of the given large-scale radiology image database.

##### Abstract (translated by Google)
在大规模放射学图像数据库中获取语义标签（来自61,845名独特患者的215786个关键图像）是培养高效的深度卷积神经网络（CNN）图像识别模型的先决条件和瓶颈。尽管如此，传统的收集图像标签的方法（例如Google搜索之后是群众采购）并不适用，因为对于那些没有经过临床培训的人来说，医学注释任务的难度很大。即使是放射科医师，由于不确定性和可能剧烈的观察者间差异或不一致性，这种类型的图像标记任务仍然是不平凡的。在本文中，我们提出了一个视觉连贯和临床语义（概念）集群自动类别发现的环形深伪任务优化程序。我们的系统可以通过特定领域（CNN在放射图像和文本报告派生标签上培训）或通用（基于ImageNet的）CNN模型进行初始化。之后，利用新的标签（以获得更多的任务代表深度特征），利用环形深度图像特征聚类（细化图像标签）和深度CNN训练/分类利用伪任务序列。我们的方法在概念上是简单的，并基于较好标签的假设“收敛”，导致更好的训练CNN模型，反过来喂养更有效的深层图像特征，以促进更有意义的聚类/标签。我们通过实证验证了这种趋同性，并展现了有希望的定量和定性结果。发现质量明显高于以前工作的类别标签。这允许进一步调查给定的大规模放射图像数据库的分级语义性质。

##### URL
[https://arxiv.org/abs/1603.07965](https://arxiv.org/abs/1603.07965)

##### PDF
[https://arxiv.org/pdf/1603.07965](https://arxiv.org/pdf/1603.07965)

