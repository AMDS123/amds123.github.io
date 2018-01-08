---
layout: post
title: "Combination of Hyperband and Bayesian Optimization for Hyperparameter Optimization in Deep Learning"
date: 2018-01-05 01:00:03
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning
author: Jiazhuo Wang, Jason Xu, Xuejun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has achieved impressive results on many problems. However, it requires high degree of expertise or a lot of experience to tune well the hyperparameters, and such manual tuning process is likely to be biased. Moreover, it is not practical to try out as many different hyperparameter configurations in deep learning as in other machine learning scenarios, because evaluating each single hyperparameter configuration in deep learning would mean training a deep neural network, which usually takes quite long time. Hyperband algorithm achieves state-of-the-art performance on various hyperparameter optimization problems in the field of deep learning. However, Hyperband algorithm does not utilize history information of previous explored hyperparameter configurations, thus the solution found is suboptimal. We propose to combine Hyperband algorithm with Bayesian optimization (which does not ignore history when sampling next trial configuration). Experimental results show that our combination approach is superior to other hyperparameter optimization approaches including Hyperband algorithm.

##### Abstract (translated by Google)
深度学习在许多问题上取得了可观的成果。然而，这需要高度的专业知识或丰富的经验来调整超参数，而这种手动调整过程可能会有偏差。此外，在其他机器学习场景中尝试深度学习中的许多不同超参数配置是不实际的，因为在深度学习中评估每个单个超参数配置将意味着训练通常需要相当长时间的深度神经网络。超宽带算法在深度学习领域的各种超参数优化问题上达到了最先进的性能。然而，超频带算法不利用先前探索的超参数配置的历史信息，因此发现的解决方案是不理想的。我们建议将Hyperband算法与贝叶斯优化相结合（在采样下一个试验配置时不会忽略历史）。实验结果表明，我们的组合方法优于包括Hyperband算法在内的其他超参数优化方法。

##### URL
[http://arxiv.org/abs/1801.01596](http://arxiv.org/abs/1801.01596)

##### PDF
[http://arxiv.org/pdf/1801.01596](http://arxiv.org/pdf/1801.01596)

