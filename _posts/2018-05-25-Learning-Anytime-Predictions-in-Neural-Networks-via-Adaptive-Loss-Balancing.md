---
layout: post
title: "Learning Anytime Predictions in Neural Networks via Adaptive Loss Balancing"
date: 2018-05-25 05:18:33
categories: arXiv_AI
tags: arXiv_AI Prediction Recognition
author: Hanzhang Hu, Debadeepta Dey, Martial Hebert, J. Andrew Bagnell
mathjax: true
---

* content
{:toc}

##### Abstract
This work considers the trade-off between accuracy and test-time computational cost of deep neural networks (DNNs) via \emph{anytime} predictions from auxiliary predictions. Specifically, we optimize auxiliary losses jointly in an \emph{adaptive} weighted sum, where the weights are inversely proportional to average of each loss. Intuitively, this balances the losses to have the same scale. We demonstrate theoretical considerations that motivate this approach from multiple viewpoints, including connecting it to optimizing the geometric mean of the expectation of each loss, an objective that ignores the scale of losses. Experimentally, the adaptive weights induce more competitive anytime predictions on multiple recognition data-sets and models than non-adaptive approaches including weighing all losses equally. In particular, anytime neural networks (ANNs) can achieve the same accuracy faster using adaptive weights on a small network than using static constant weights on a large one. For problems with high performance saturation, we also show a sequence of exponentially deepening ANNscan achieve near-optimal anytime results at any budget, at the cost of a const fraction of extra computation.

##### Abstract (translated by Google)
这项工作考虑了来自辅助预测的\ emph {anytime}预测在深度神经网络（DNN）的准确度和测试时间计算成本之间的折衷。具体而言，我们在一个\ emph {自适应}加权总和中优化辅助损失，其中权重与每个损失的平均值成反比。直观地说，这可以平衡损失，使其具有相同的规模。我们从多个角度论证了激励这种方法的理论考虑因素，包括将它与优化每个损失期望的几何平均数相结合，这是一个忽略损失规模的目标。在实验上，自适应权重会导致更多的竞争对多个识别数据集和模型的预测比非自适应方法包括权衡所有损失平等。特别是，任何时候，神经网络（ANN）都可以使用小网络上的自适应权重更快地达到相同的精度，而不是使用大的静态恒定权重。对于高性能饱和问题，我们还展示了一系列指数级加深的ANNscan可以在任何预算下实现近乎最优的任何时间结果，但需要花费额外计算的常数。

##### URL
[http://arxiv.org/abs/1708.06832](http://arxiv.org/abs/1708.06832)

##### PDF
[http://arxiv.org/pdf/1708.06832](http://arxiv.org/pdf/1708.06832)

