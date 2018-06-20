---
layout: post
title: "Neural Ordinary Differential Equations"
date: 2018-06-19 17:50:12
categories: arXiv_AI
tags: arXiv_AI
author: Tian Qi Chen, Yulia Rubanova, Jesse Bettencourt, David Duvenaud
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new family of deep neural network models. Instead of specifying a discrete sequence of hidden layers, we parameterize the derivative of the hidden state using a neural network. The output of the network is computed using a blackbox differential equation solver. These continuous-depth models have constant memory cost, adapt their evaluation strategy to each input, and can explicitly trade numerical precision for speed. We demonstrate these properties in continuous-depth residual networks and continuous-time latent variable models. We also construct continuous normalizing flows, a generative model that can train by maximum likelihood, without partitioning or ordering the data dimensions. For training, we show how to scalably backpropagate through any ODE solver, without access to its internal operations. This allows end-to-end training of ODEs within larger models.

##### Abstract (translated by Google)
我们引入了一个新的深度神经网络模型家族。我们不使用隐含层的离散序列，而是使用神经网络对隐藏状态的导数进行参数化。网络的输出使用黑箱微分方程求解器来计算。这些连续深度模型具有不断的记忆成本，使其评估策略适应每个输入，并且可以明确交换数值精度以获得速度。我们在连续深度残差网络和连续时间潜变量模型中证明了这些性质。我们还构建连续标准化流程，这是一种可以通过最大可能性进行训练的生成模型，无需对数据维度进行分区或排序。对于培训，我们展示了如何通过任何ODE求解器进行可扩展反向传播，而无需访问其内部操作。这允许在较大模型内进行ODE的端到端培训。

##### URL
[http://arxiv.org/abs/1806.07366](http://arxiv.org/abs/1806.07366)

##### PDF
[http://arxiv.org/pdf/1806.07366](http://arxiv.org/pdf/1806.07366)

