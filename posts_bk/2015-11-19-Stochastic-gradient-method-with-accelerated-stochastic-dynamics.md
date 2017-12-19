---
layout: post
title: "Stochastic gradient method with accelerated stochastic dynamics"
date: 2015-11-19 01:01:59
categories: arXiv_CV
tags: arXiv_CV Relation
author: Masayuki Ohzeki
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel technique to implement stochastic gradient methods, which are beneficial for learning from large datasets, through accelerated stochastic dynamics. A stochastic gradient method is based on mini-batch learning for reducing the computational cost when the amount of data is large. The stochasticity of the gradient can be mitigated by the injection of Gaussian noise, which yields the stochastic Langevin gradient method; this method can be used for Bayesian posterior sampling. However, the performance of the stochastic Langevin gradient method depends on the mixing rate of the stochastic dynamics. In this study, we propose violating the detailed balance condition to enhance the mixing rate. Recent studies have revealed that violating the detailed balance condition accelerates the convergence to a stationary state and reduces the correlation time between the samplings. We implement this violation of the detailed balance condition in the stochastic gradient Langevin method and test our method for a simple model to demonstrate its performance.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的技术来实现随机梯度方法，这有利于从大型数据集的学习，通过加速的随机动态。随机梯度法是基于小批量学习，在数据量较大时降低计算成本。通过注入高斯噪声可以减轻梯度的随机性，产生随机Langevin梯度法;这种方法可以用于贝叶斯后验采样。然而，随机Langevin梯度法的性能取决于随机动力学的混合率。在这项研究中，我们建议违反详细的平衡条件来提高混合率。最近的研究表明，违反详细的平衡条件会加速收敛到静止状态，缩短采样间的相关时间。我们在随机梯度Langevin方法中实现了这个违背了详细平衡条件的问题，并用一个简单的模型来验证我们的方法来证明它的性能。

##### URL
[https://arxiv.org/abs/1511.06036](https://arxiv.org/abs/1511.06036)

##### PDF
[https://arxiv.org/pdf/1511.06036](https://arxiv.org/pdf/1511.06036)

