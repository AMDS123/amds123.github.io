---
layout: post
title: "Belief Propagation in Conditional RBMs for Structured Prediction"
date: 2017-03-02 23:28:53
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Wei Ping, Alexander Ihler
mathjax: true
---

* content
{:toc}

##### Abstract
Restricted Boltzmann machines~(RBMs) and conditional RBMs~(CRBMs) are popular models for a wide range of applications. In previous work, learning on such models has been dominated by contrastive divergence~(CD) and its variants. Belief propagation~(BP) algorithms are believed to be slow for structured prediction on conditional RBMs~(e.g., Mnih et al. [2011]), and not as good as CD when applied in learning~(e.g., Larochelle et al. [2012]). In this work, we present a matrix-based implementation of belief propagation algorithms on CRBMs, which is easily scalable to tens of thousands of visible and hidden units. We demonstrate that, in both maximum likelihood and max-margin learning, training conditional RBMs with BP as the inference routine can provide significantly better results than current state-of-the-art CD methods on structured prediction problems. We also include practical guidelines on training CRBMs with BP, and some insights on the interaction of learning and inference algorithms for CRBMs.

##### Abstract (translated by Google)
受限玻尔兹曼机器（RBM）和条件RBM〜（CRBM）是广泛应用的流行模型。在以前的工作中，对这种模型的学习主要是对比分歧〜（CD）及其变体。相信传播〜（BP）算法被认为是有条件的RBM结构预测缓慢的（例如，Mnih等人[2011]），并且在学习中不如CD时好（例如，Larochelle等人[ 2012]）。在这项工作中，我们提出了一个基于矩阵的CRBM上的信任传播算法的实现，它可以容易地扩展到数以万计的可见和隐藏的单位。我们证明，在最大似然和最大边缘学习中，以BP作为推理例程的条件RBM训练可以提供比当前最先进的CD方法在结构预测问题上显着更好的结果。我们还包括关于使用BP来培训CRBM的实用指南，以及关于CRBM的学习和推理算法的交互的一些见解。

##### URL
[https://arxiv.org/abs/1703.00986](https://arxiv.org/abs/1703.00986)

##### PDF
[https://arxiv.org/pdf/1703.00986](https://arxiv.org/pdf/1703.00986)

