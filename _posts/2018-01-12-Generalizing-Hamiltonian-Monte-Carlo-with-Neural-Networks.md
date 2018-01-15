---
layout: post
title: "Generalizing Hamiltonian Monte Carlo with Neural Networks"
date: 2018-01-12 06:55:12
categories: arXiv_AI
tags: arXiv_AI Quantitative
author: Daniel Levy, Matthew D. Hoffman, Jascha Sohl-Dickstein
mathjax: true
---

* content
{:toc}

##### Abstract
We present a general-purpose method to train Markov chain Monte Carlo kernels, parameterized by deep neural networks, that converge and mix quickly to their target distribution. Our method generalizes Hamiltonian Monte Carlo and is trained to maximize expected squared jumped distance, a proxy for mixing speed. We demonstrate large empirical gains on a collection of simple but challenging distributions, for instance achieving a 106x improvement in effective sample size in one case, and mixing when standard HMC makes no measurable progress in a second. Finally, we show quantitative and qualitative gains on a real-world task: latent-variable generative modeling. We release an open source TensorFlow implementation of the algorithm.

##### Abstract (translated by Google)
我们提出了一种通用的方法来训练马尔科夫链蒙特卡罗核，由深度神经网络参数化，收敛和快速混合到他们的目标分布。我们的方法概括哈密尔顿蒙特卡罗和训练最大化预期平方跳跃距离，代理混合速度。我们在简单但具有挑战性的分布集合上证明了大量的经验收益，例如在一种情况下实现了有效样本规模的106倍改进，以及当标准HMC在一秒钟内没有可衡量的进展时混合。最后，我们展示了一个真实世界任务的定量和定性收益：潜变量生成建模。我们发布了一个开源的TensorFlow算法实现。

##### URL
[http://arxiv.org/abs/1711.09268](http://arxiv.org/abs/1711.09268)

##### PDF
[http://arxiv.org/pdf/1711.09268](http://arxiv.org/pdf/1711.09268)

