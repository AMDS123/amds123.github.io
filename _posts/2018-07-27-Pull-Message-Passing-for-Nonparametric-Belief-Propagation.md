---
layout: post
title: "Pull Message Passing for Nonparametric Belief Propagation"
date: 2018-07-27 08:24:55
categories: arXiv_CV
tags: arXiv_CV Inference
author: Karthik Desingh, Anthony Opipari, Odest Chadwicke Jenkins
mathjax: true
---

* content
{:toc}

##### Abstract
We present a "pull" approach to approximate products of Gaussian mixtures within message updates for Nonparametric Belief Propagation (NBP) inference. Existing NBP methods often represent messages between continuous-valued latent variables as Gaussian mixture models. To avoid computational intractability in loopy graphs, NBP necessitates an approximation of the product of such mixtures. Sampling-based product approximations have shown effectiveness for NBP inference. However, such approximations used within the traditional "push" message update procedures quickly become computationally prohibitive for multi-modal distributions over high-dimensional variables. In contrast, we propose a "pull" method, as the Pull Message Passing for Nonparametric Belief propagation (PMPNBP) algorithm, and demonstrate its viability for efficient inference. We report results using an experiment from an existing NBP method, PAMPAS, for inferring the pose of an articulated structure in clutter. Results from this illustrative problem found PMPNBP has a greater ability to efficiently scale the number of components in its mixtures and, consequently, improve inference accuracy.

##### Abstract (translated by Google)
我们提出了一种“拉”方法，用于在非参数置信传播（NBP）推理的消息更新中近似高斯混合的乘积。现有的NBP方法通常将连续值潜在变量之间的消息表示为高斯混合模型。为了避免循环图中的计算难以处理，NBP需要近似这种混合物的乘积。基于抽样的产品近似已显示NBP推断的有效性。然而，在传统的“推送”消息更新过程中使用的这种近似很快变得对于高维变量的多模态分布在计算上是禁止的。相比之下，我们提出了一种“拉”方法，作为非参数信念传播的拉消息传递（PMPNBP）算法，并证明了其有效推理的可行性。我们使用现有NBP方法PAMPAS的实验报告结果，用于推断杂波中铰接结构的姿态。该说明性问题的结果发现PMPNBP具有更高的能力来有效地扩展其混合物中的组分数量，并因此提高推理准确度。

##### URL
[http://arxiv.org/abs/1807.10487](http://arxiv.org/abs/1807.10487)

##### PDF
[http://arxiv.org/pdf/1807.10487](http://arxiv.org/pdf/1807.10487)

