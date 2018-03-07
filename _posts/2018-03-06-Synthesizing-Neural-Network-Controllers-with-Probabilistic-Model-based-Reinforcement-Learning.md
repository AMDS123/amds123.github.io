---
layout: post
title: "Synthesizing Neural Network Controllers with Probabilistic Model based Reinforcement Learning"
date: 2018-03-06 16:42:46
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Juan Camilo Gamboa Higuera, David Meger, Gregory Dudek
mathjax: true
---

* content
{:toc}

##### Abstract
We present an algorithm for rapidly learning controllers for robotics systems. The algorithm follows the model-based reinforcement learning paradigm, and improves upon existing algorithms; namely Probabilistic learning in Control (PILCO) and a sample-based version of PILCO with neural network dynamics (Deep-PILCO). We propose training a neural network dynamics model using variational dropout with truncated Log-Normal noise. This allows us to obtain a dynamics model with calibrated uncertainty, which can be used to simulate controller executions via rollouts. We also describe set of techniques, inspired by viewing PILCO as a recurrent neural network model, that are crucial to improve the convergence of the method. We test our method on a variety of benchmark tasks, demonstrating data-efficiency that is competitive with PILCO, while being able to optimize complex neural network controllers. Finally, we assess the performance of the algorithm for learning motor controllers for a six legged autonomous underwater vehicle. This demonstrates the potential of the algorithm for scaling up the dimensionality and dataset sizes, in more complex control tasks.

##### Abstract (translated by Google)
我们提出了一种快速学习机器人系统控制器的算法。该算法遵循基于模型的强化学习范例，并改进现有算法;即控制中的概率学习（PILCO）和基于样本的PILCO与神经网络动力学（Deep-PILCO）。我们提出使用具有截尾对数正态噪声的变分丢失来训练神经网络动力学模型。这使我们能够获得具有校准不确定度的动态模型，这可用于模拟控制器通过铺开执行。我们还描述了一系列技术，这些技术受PILCO作为递归神经网络模型的启发，这对于改进方法的收敛性至关重要。我们在各种基准任务上测试我们的方法，展示与PILCO相竞争的数据效率，同时能够优化复杂的神经网络控制器。最后，我们评估了用于学习六腿自主水下航行器的电机控制器的算法的性能。这证明了该算法在更复杂的控制任务中扩展维度和数据集大小的潜力。

##### URL
[http://arxiv.org/abs/1803.02291](http://arxiv.org/abs/1803.02291)

##### PDF
[http://arxiv.org/pdf/1803.02291](http://arxiv.org/pdf/1803.02291)

