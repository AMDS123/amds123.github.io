---
layout: post
title: "PAC-Bayes Control: Synthesizing Controllers that Provably Generalize to Novel Environments"
date: 2018-06-11 20:23:25
categories: arXiv_AI
tags: arXiv_AI Optimization Gradient_Descent
author: Anirudha Majumdar, Maxwell Goldstein
mathjax: true
---

* content
{:toc}

##### Abstract
Our goal is to synthesize controllers for robots that provably generalize well to novel environments given a dataset of example environments. The key technical idea behind our approach is to leverage tools from generalization theory in machine learning by exploiting a precise analogy (which we present in the form of a reduction) between robustness of controllers to novel environments and generalization of hypotheses in supervised learning. In particular, we utilize the Probably Approximately Correct (PAC)-Bayes framework, which allows us to obtain upper bounds (that hold with high probability) on the expected cost of (stochastic) controllers across novel environments. We propose control synthesis algorithms that explicitly seek to minimize this upper bound. The corresponding optimization problem can be solved using convex optimization (Relative Entropy Programming in particular) in the setting where we are optimizing over a finite control policy space. In the more general setting of continuously parameterized controllers, we minimize this upper bound using stochastic gradient descent. We present examples of our approach in the context of obstacle avoidance control with depth measurements. Our simulated examples demonstrate the potential of our approach to provide strong generalization guarantees on controllers for robotic systems with continuous state and action spaces, complicated (e.g., nonlinear) dynamics, and rich sensory inputs (e.g., depth measurements).

##### Abstract (translated by Google)
我们的目标是综合用于机器人的控制器，这些控制器可以很好地推广到给定示例环境数据集的新环境。我们方法背后的关键技术理念是利用机器学习中泛化理论中的工具，利用控制器对新环境的鲁棒性和监督学习中假设的泛化之间的精确类比（我们以减少的形式呈现）。特别是，我们使用了可能近似正确（PAC）-Bayes框架，该框架允许我们在新环境中获得（随机）控制器的预期成本的上界（以高概率保持）。我们提出控制综合算法，明确寻求最小化这个上限。相应的优化问题可以使用凸优化（特别是相对熵编程）在我们正在优化有限控制策略空间的环境中解决。在更一般的连续参数化控制器设置中，我们使用随机梯度下降来最小化这个上限。我们在深度测量的避障控制背景下举例说明了我们的方法。我们的仿真实例证明了我们的方法为具有连续状态和动作空间，复杂（例如，非线性）动力学和丰富感觉输入（例如深度测量）的机器人系统的控制器提供强泛化保证的潜力。

##### URL
[http://arxiv.org/abs/1806.04225](http://arxiv.org/abs/1806.04225)

##### PDF
[http://arxiv.org/pdf/1806.04225](http://arxiv.org/pdf/1806.04225)

