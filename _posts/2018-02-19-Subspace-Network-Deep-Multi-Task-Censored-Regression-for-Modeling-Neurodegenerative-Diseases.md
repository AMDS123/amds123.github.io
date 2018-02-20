---
layout: post
title: "Subspace Network: Deep Multi-Task Censored Regression for Modeling Neurodegenerative Diseases"
date: 2018-02-19 04:50:14
categories: arXiv_AI
tags: arXiv_AI Knowledge Prediction
author: Mengying Sun, Inci M. Baytas, Liang Zhan, Zhangyang Wang, Jiayu Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past decade a wide spectrum of machine learning models have been developed to model the neurodegenerative diseases, associating biomarkers, especially non-intrusive neuroimaging markers, with key clinical scores measuring the cognitive status of patients. Multi-task learning (MTL) has been commonly utilized by these studies to address high dimensionality and small cohort size challenges. However, most existing MTL approaches are based on linear models and suffer from two major limitations: 1) they cannot explicitly consider upper/lower bounds in these clinical scores; 2) they lack the capability to capture complicated non-linear interactions among the variables. In this paper, we propose Subspace Network, an efficient deep modeling approach for non-linear multi-task censored regression. Each layer of the subspace network performs a multi-task censored regression to improve upon the predictions from the last layer via sketching a low-dimensional subspace to perform knowledge transfer among learning tasks. Under mild assumptions, for each layer the parametric subspace can be recovered using only one pass of training data. Empirical results demonstrate that the proposed subspace network quickly picks up the correct parameter subspaces, and outperforms state-of-the-arts in predicting neurodegenerative clinical scores using information in brain imaging.

##### Abstract (translated by Google)
在过去的十年中，已经开发了多种机器学习模型来模拟神经变性疾病，将生物标志物（特别是非侵入性神经影像学标志物）与关键临床评分关联起来，测量患者的认知状态。这些研究通常利用多任务学习（MTL）来解决高维度和小群体大小挑战。然而，大多数现有的MTL方法都是基于线性模型，并受到两个主要限制：1）他们不能明确考虑这些临床评分的上限/下限; 2）他们缺乏捕捉变量之间复杂的非线性相互作用的能力。在本文中，我们提出子空间网络，一种用于非线性多任务删失回归的高效深度建模方法。子空间网络的每一层执行多任务审查回归，以通过绘制低维子空间以在学习任务之间执行知识转移来改进来自最后一层的预测。在温和的假设下，对于每一层，参数子空间可以仅使用一次训练数据来恢复。实证结果表明，所提出的子空间网络可快速获取正确的参数子空间，并且在使用脑成像信息预测神经退行性临床评分方面优于现有技术。

##### URL
[http://arxiv.org/abs/1802.06516](http://arxiv.org/abs/1802.06516)

##### PDF
[http://arxiv.org/pdf/1802.06516](http://arxiv.org/pdf/1802.06516)

