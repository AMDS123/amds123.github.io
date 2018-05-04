---
layout: post
title: "Boosting Domain Adaptation by Discovering Latent Domains"
date: 2018-05-03 15:55:48
categories: arXiv_CV
tags: arXiv_CV CNN
author: Massimiliano Mancini, Lorenzo Porzi, Samuel Rota Bul&#xf2;, Barbara Caputo, Elisa Ricci
mathjax: true
---

* content
{:toc}

##### Abstract
Current Domain Adaptation (DA) methods based on deep architectures assume that the source samples arise from a single distribution. However, in practice, most datasets can be regarded as mixtures of multiple domains. In these cases exploiting single-source DA methods for learning target classifiers may lead to sub-optimal, if not poor, results. In addition, in many applications it is difficult to manually provide the domain labels for all source data points, i.e. latent domains should be automatically discovered. This paper introduces a novel Convolutional Neural Network (CNN) architecture which (i) automatically discovers latent domains in visual datasets and (ii) exploits this information to learn robust target classifiers. Our approach is based on the introduction of two main components, which can be embedded into any existing CNN architecture: (i) a side branch that automatically computes the assignment of a source sample to a latent domain and (ii) novel layers that exploit domain membership information to appropriately align the distribution of the CNN internal feature representations to a reference distribution. We test our approach on publicly-available datasets, showing that it outperforms state-of-the-art multi-source DA methods by a large margin.

##### Abstract (translated by Google)
基于深层体系结构的当前域适配（DA）方法假设源样本来自单一分布。但是，实际上，大多数数据集可以被视为多个域的混合。在这些情况下，利用单源DA方法学习目标分类器可能会导致次优，即使不是很差的结果。另外，在许多应用中，手动为所有源数据点提供域标签是困难的，即应该自动发现潜域。本文介绍了一种新颖的卷积神经网络（CNN）体系结构，它（i）自动发现视觉数据集中的潜在域，并（ii）利用这些信息来学习鲁棒的目标分类器。我们的方法基于两个主要组件的介绍，它们可以嵌入到任何现有的CNN架构中：（i）自动计算源样本到潜在域的分配的侧分支和（ii）利用域的新颖层会员信息以适当地将CNN内部特征表示的分布与参考分布对齐。我们在公开可用的数据集上测试了我们的方法，显示它在很大程度上优于最先进的多源DA方法。

##### URL
[http://arxiv.org/abs/1805.01386](http://arxiv.org/abs/1805.01386)

##### PDF
[http://arxiv.org/pdf/1805.01386](http://arxiv.org/pdf/1805.01386)

