---
layout: post
title: "The Nonlinearity Coefficient - Predicting Overfitting in Deep Neural Networks"
date: 2018-06-01 03:58:14
categories: arXiv_CV
tags: arXiv_CV
author: George Philipp, Jaime G. Carbonell
mathjax: true
---

* content
{:toc}

##### Abstract
For a long time, designing neural architectures that exhibit high performance was considered a dark art that required expert hand-tuning. One of the few well-known guidelines for architecture design is the avoidance of exploding gradients, though even this guideline has remained relatively vague and circumstantial. We introduce the nonlinearity coefficient (NLC), a measurement of the complexity of the function computed by a neural network that is based on the magnitude of the gradient. Via an extensive empirical study, we show that the NLC is a powerful predictor of test error and that attaining a right-sized NLC is essential for optimal performance. 
 The NLC exhibits a range of intriguing and important properties. It is closely tied to the amount of information gained from computing a single network gradient. It is tied to the error incurred when replacing the nonlinearity operations in the network with linear operations. It is not susceptible to the confounders of multiplicative scaling, additive bias and layer width. It is stable from layer to layer. Hence, we argue that the NLC is the first robust predictor of overfitting in deep networks.

##### Abstract (translated by Google)
长期以来，设计表现出高性能的神经架构被认为是需要专家手动调整的黑暗艺术。为数不多的众所周知的建筑设计准则之一是避免了梯度的爆炸，尽管这个准则仍然相对模糊和间接。我们引入非线性系数（NLC），这是一种基于梯度大小的神经网络计算函数复杂性的度量。通过广泛的实证研究，我们证明NLC是测试错误的强大预测因子，并且获得正确尺寸的NLC对于获得最佳性能至关重要。
 NLC展示了一系列有趣且重要的特性。它与计算单个网络梯度所获得的信息量密切相关。它与用线性运算代替网络中的非线性运算时产生的误差有关。它不容易受到倍增缩放，叠加偏移和层宽的混杂因素影响。它从一层到另一层都是稳定的。因此，我们认为NLC是深度网络中过度拟合的第一个强有力的预测器。

##### URL
[http://arxiv.org/abs/1806.00179](http://arxiv.org/abs/1806.00179)

##### PDF
[http://arxiv.org/pdf/1806.00179](http://arxiv.org/pdf/1806.00179)

