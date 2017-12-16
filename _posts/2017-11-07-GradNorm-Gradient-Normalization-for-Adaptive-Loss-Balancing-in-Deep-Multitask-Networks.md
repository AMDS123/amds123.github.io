---
layout: post
title: "GradNorm: Gradient Normalization for Adaptive Loss Balancing in Deep Multitask Networks"
date: 2017-11-07 02:08:12
categories: arXiv_CV
tags: arXiv_CV Classification
author: Zhao Chen, Vijay Badrinarayanan, Chen-Yu Lee, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
Deep multitask networks, in which one neural network produces multiple predictive outputs, are more scalable and often better regularized than their single-task counterparts. Such advantages can potentially lead to gains in both speed and performance, but multitask networks are also difficult to train without finding the right balance between tasks. We present a novel gradient normalization (GradNorm) technique which automatically balances the multitask loss function by directly tuning the gradients to equalize task training rates. We show that for various network architectures, for both regression and classification tasks, and on both synthetic and real datasets, GradNorm improves accuracy and reduces overfitting over single networks, static baselines, and other adaptive multitask loss balancing techniques. GradNorm also matches or surpasses the performance of exhaustive grid search methods, despite only involving a single asymmetry hyperparameter $\alpha$. Thus, what was once a tedious search process which incurred exponentially more compute for each task added can now be accomplished within a few training runs, irrespective of the number of tasks. Ultimately, we hope to demonstrate that direct gradient manipulation affords us great control over the training dynamics of multitask networks and may be one of the keys to unlocking the potential of multitask learning.

##### Abstract (translated by Google)
深度多任务网络（其中一个神经网络产生多个预测输出）比其单任务对手更具可扩展性并且通常更好地正规化。这样的优势可能会带来速度和性能的提升，但是多任务网络也很难在没有找到适当的任务平衡的情况下进行训练。我们提出了一种新的梯度归一化（GradNorm）技术，通过直接调整梯度来均衡任务训练速率，自动平衡多任务损失函数。我们展示了对于各种网络体系结构，对于回归和分类任务以及合成和真实数据集，GradNorm提高了准确性并减少了对单一网络，静态基线和其他自适应多任务丢失平衡技术的过度拟合。尽管只涉及单个不对称超参数$ \ alpha $，GradNorm也匹配或超过穷举网格搜索方法的性能。因此，无论任务的数量如何，在一些训练运行中，现在可以完成的是曾经繁琐的搜索过程，其对于每个添加的任务而言指数地更多的计算。最终，我们希望证明直接梯度操纵能够让我们对多任务网络的训练动态有很好的控制，并且可能是解开多任务学习潜力的关键之一。

##### URL
[https://arxiv.org/abs/1711.02257](https://arxiv.org/abs/1711.02257)

##### PDF
[https://arxiv.org/pdf/1711.02257](https://arxiv.org/pdf/1711.02257)

