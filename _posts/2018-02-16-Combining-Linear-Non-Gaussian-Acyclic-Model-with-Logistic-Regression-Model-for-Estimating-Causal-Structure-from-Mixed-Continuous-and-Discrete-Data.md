---
layout: post
title: "Combining Linear Non-Gaussian Acyclic Model with Logistic Regression Model for Estimating Causal Structure from Mixed Continuous and Discrete Data"
date: 2018-02-16 10:45:59
categories: arXiv_AI
tags: arXiv_AI
author: Chao Li, Shohei Shimizu
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating causal models from observational data is a crucial task in data analysis. For continuous-valued data, Shimizu et al. have proposed a linear acyclic non-Gaussian model to understand the data generating process, and have shown that their model is identifiable when the number of data is sufficiently large. However, situations in which continuous and discrete variables coexist in the same problem are common in practice. Most existing causal discovery methods either ignore the discrete data and apply a continuous-valued algorithm or discretize all the continuous data and then apply a discrete Bayesian network approach. These methods possibly loss important information when we ignore discrete data or introduce the approximation error due to discretization. In this paper, we define a novel hybrid causal model which consists of both continuous and discrete variables. The model assumes: (1) the value of a continuous variable is a linear function of its parent variables plus a non-Gaussian noise, and (2) each discrete variable is a logistic variable whose distribution parameters depend on the values of its parent variables. In addition, we derive the BIC scoring function for model selection. The new discovery algorithm can learn causal structures from mixed continuous and discrete data without discretization. We empirically demonstrate the power of our method through thorough simulations.

##### Abstract (translated by Google)
从观测数据估计因果模型是数据分析中的一项重要任务。对于连续有价值的数据，Shimizu et al。已经提出了一个线性非循环非高斯模型来理解数据生成过程，并且已经表明，当数据数量足够大时，它们的模型是可识别的。然而，连续和离散变量共存于相同问题的情况在实践中很常见。大多数现有的因果发现方法要么忽略离散数据并应用连续值算法，要么离散化所有连续数据，然后应用离散贝叶斯网络方法。当我们忽略离散数据或由于离散化引入近似误差时，这些方法可能会丢失重要信息。在本文中，我们定义了一个由连续变量和离散变量组成的新型混合因果模型。该模型假定：（1）连续变量的值是其父变量加上非高斯噪声的线性函数，（2）每个离散变量是逻辑变量，其分布参数取决于其父变量的值。另外，我们推导了用于模型选择的BIC评分函数。新的发现算法可以从混合连续数据和离散数据中学习因果结构，而无需离散化。我们通过全面的模拟实验证明了我们方法的强大功能。

##### URL
[https://arxiv.org/abs/1802.05889](https://arxiv.org/abs/1802.05889)

##### PDF
[https://arxiv.org/pdf/1802.05889](https://arxiv.org/pdf/1802.05889)

