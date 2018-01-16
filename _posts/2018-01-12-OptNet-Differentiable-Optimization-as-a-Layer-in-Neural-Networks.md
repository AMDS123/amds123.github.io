---
layout: post
title: "OptNet: Differentiable Optimization as a Layer in Neural Networks"
date: 2018-01-12 19:44:25
categories: arXiv_AI
tags: arXiv_AI CNN Optimization
author: Brandon Amos, J. Zico Kolter
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents OptNet, a network architecture that integrates optimization problems (here, specifically in the form of quadratic programs) as individual layers in larger end-to-end trainable deep networks. These layers encode constraints and complex dependencies between the hidden states that traditional convolutional and fully-connected layers often cannot capture. In this paper, we explore the foundations for such an architecture: we show how techniques from sensitivity analysis, bilevel optimization, and implicit differentiation can be used to exactly differentiate through these layers and with respect to layer parameters; we develop a highly efficient solver for these layers that exploits fast GPU-based batch solves within a primal-dual interior point method, and which provides backpropagation gradients with virtually no additional cost on top of the solve; and we highlight the application of these approaches in several problems. In one notable example, we show that the method is capable of learning to play mini-Sudoku (4x4) given just input and output games, with no a priori information about the rules of the game; this highlights the ability of our architecture to learn hard constraints better than other neural architectures.

##### Abstract (translated by Google)
本文介绍OptNet，这是一种网络架构，将大型端到端可训练深度网络中的优化问题（这里，特别是以二次方案的形式）作为独立层次集成在一起。这些层对传统卷积层和完全连接层通常无法捕获的隐藏状态之间的约束和复杂依赖进行编码。在本文中，我们探讨了这样一个架构的基础：我们展示了如何使用灵敏度分析，双层优化和隐式区分的技术来精确地区分这些层和层参数。我们针对这些层开发了一种高效的求解器，这种求解器在原始 - 双重内点方法中利用基于GPU的快速批处理解决方案，并且在求解之上提供反向传播梯度，几乎不需要额外的成本;我们强调这些方法在几个问题上的应用。在一个值得注意的例子中，我们展示了这种方法能够学习玩迷你Sudoku（4x4），只需要输入和输出游戏，没有关于游戏规则的先验信息。这突出显示了我们的架构比其他神经架构更好地学习硬约束的能力。

##### URL
[http://arxiv.org/abs/1703.00443](http://arxiv.org/abs/1703.00443)

##### PDF
[http://arxiv.org/pdf/1703.00443](http://arxiv.org/pdf/1703.00443)

