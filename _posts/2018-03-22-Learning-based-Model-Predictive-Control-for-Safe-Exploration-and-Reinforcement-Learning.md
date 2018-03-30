---
layout: post
title: "Learning-based Model Predictive Control for Safe Exploration and Reinforcement Learning"
date: 2018-03-22 09:41:45
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Prediction
author: Torsten Koller, Felix Berkenkamp, Matteo Turchetta, Andreas Krause
mathjax: true
---

* content
{:toc}

##### Abstract
Learning-based methods have been successful in solving complex control tasks without significant prior knowledge about the system. However, these methods typically do not provide any safety guarantees, which prevents their use in safety-critical, real-world applications. In this paper, we present a learning-based model predictive control scheme that provides provable high-probability safety guarantees. To this end, we exploit regularity assumptions on the dynamics in terms of a Gaussian process prior to construct provably accurate confidence intervals on predicted trajectories. Unlike previous approaches, we do not assume that model uncertainties are independent. Based on these predictions, we guarantee that trajectories satisfy safety constraints. Moreover, we use a terminal set constraint to recursively guarantee the existence of safe control actions at every iteration. In our experiments, we show that the resulting algorithm can be used to safely and efficiently explore and learn about dynamic systems.

##### Abstract (translated by Google)
基于学习的方法已经成功地解决了复杂的控制任务，而没有关于系统的大量先验知识。但是，这些方法通常不提供任何安全保证，这妨碍了它们在安全关键的现实应用中的使用。在本文中，我们提出了一个基于学习的模型预测控制方案，提供可证明的高概率安全保证。为此，我们在构建预测轨迹的准确置信区间之前，利用高斯过程的动力学规律性假设。与以前的方法不同，我们不假定模型不确定性是独立的。根据这些预测，我们保证轨迹满足安全限制。此外，我们使用终端集约束来递归确保每次迭代都存在安全控制操作。在我们的实验中，我们证明了所得到的算法可以用来安全有效地探索和学习动态系统。

##### URL
[https://arxiv.org/abs/1803.08287](https://arxiv.org/abs/1803.08287)

##### PDF
[https://arxiv.org/pdf/1803.08287](https://arxiv.org/pdf/1803.08287)

