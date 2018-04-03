---
layout: post
title: "Unsupervised Correlation Analysis"
date: 2018-04-01 21:14:06
categories: arXiv_CV
tags: arXiv_CV Optimization Relation
author: Yedid Hoshen, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
Linking between two data sources is a basic building block in numerous computer vision problems. In this paper, we set to answer a fundamental cognitive question: are prior correspondences necessary for linking between different domains? 
 One of the most popular methods for linking between domains is Canonical Correlation Analysis (CCA). All current CCA algorithms require correspondences between the views. We introduce a new method Unsupervised Correlation Analysis (UCA), which requires no prior correspondences between the two domains. The correlation maximization term in CCA is replaced by a combination of a reconstruction term (similar to autoencoders), full cycle loss, orthogonality and multiple domain confusion terms. Due to lack of supervision, the optimization leads to multiple alternative solutions with similar scores and we therefore introduce a consensus-based mechanism that is often able to recover the desired solution. Remarkably, this suffices in order to link remote domains such as text and images. We also present results on well accepted CCA benchmarks, showing that performance far exceeds other unsupervised baselines, and approaches supervised performance in some cases.

##### Abstract (translated by Google)
两个数据源之间的链接是许多计算机视觉问题的基本组成部分。在本文中，我们将回答一个基本的认知问题：在不同领域之间进行联系需要事先对应吗？
 典型相关分析（CCA）是最常用的连接域之一的方法。目前所有的CCA算法都需要视图间的一致性。我们引入一种新的方法无监督相关分析（UCA），它不需要两个域之间的事先对应。 CCA中的相关最大化术语被重构术语（类似于自编码器），全周期损失，正交性和多领域混淆术语的组合所取代。由于缺乏监督，优化会导致多个具有相似分数的替代解决方案，因此我们引入了基于共识的机制，通常能够恢复所需的解决方案。值得注意的是，这足以连接远程域，如文本和图像。我们还提供了良好接受的CCA基准的结果，表明性能远远超过其他无监督基准，并在某些情况下接近监督表现。

##### URL
[http://arxiv.org/abs/1804.00347](http://arxiv.org/abs/1804.00347)

##### PDF
[http://arxiv.org/pdf/1804.00347](http://arxiv.org/pdf/1804.00347)

