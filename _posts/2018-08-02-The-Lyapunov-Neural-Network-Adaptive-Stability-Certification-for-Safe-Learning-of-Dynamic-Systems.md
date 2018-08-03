---
layout: post
title: "The Lyapunov Neural Network: Adaptive Stability Certification for Safe Learning of Dynamic Systems"
date: 2018-08-02 17:20:04
categories: arXiv_RO
tags: arXiv_RO Knowledge
author: Spencer M. Richards, Felix Berkenkamp, Andreas Krause
mathjax: true
---

* content
{:toc}

##### Abstract
Learning algorithms have shown considerable prowess in simulation by allowing robots to adapt to uncertain environments and improve their performance. However, such algorithms are rarely used in practice on safety-critical systems, since the learned policy typically does not yield any safety guarantees and thus the required exploration may cause physical harm to the robot or its environment. In this paper, we present a method to learn accurate safety certificates for nonlinear, closed-loop dynamic systems. Specifically, we construct a neural network Lyapunov function and a training algorithm that adapts it to the shape of the largest safe region in the state space. The algorithm relies only on knowledge of inputs and outputs of the dynamics, rather than on any specific model structure. We demonstrate our method by learning the safe region of attraction for a simulated inverted pendulum. Furthermore, we discuss how our method can be used in safe learning algorithms together with statistical models of dynamic systems.

##### Abstract (translated by Google)
通过允许机器人适应不确定的环境并改善其性能，学习算法在仿真中表现出相当的实力。然而，这种算法在安全关键系统的实践中很少使用，因为学习的策略通常不产生任何安全保证，因此所需的探索可能对机器人或其环境造成物理伤害。在本文中，我们提出了一种学习非线性闭环动态系统的准确安全证书的方法。具体来说，我们构建一个神经网络Lyapunov函数和一个训练算法，使其适应状态空间中最大安全区域的形状。该算法仅依赖于动态输入和输出的知识，而不依赖于任何特定的模型结构。我们通过学习模拟倒立摆的安全区域来演示我们的方法。此外，我们讨论了如何将我们的方法与动态系统的统计模型一起用于安全学习算法。

##### URL
[http://arxiv.org/abs/1808.00924](http://arxiv.org/abs/1808.00924)

##### PDF
[http://arxiv.org/pdf/1808.00924](http://arxiv.org/pdf/1808.00924)

