---
layout: post
title: "Safe Mutations for Deep and Recurrent Neural Networks through Output Gradients"
date: 2017-12-18 18:16:51
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning RNN Deep_Learning
author: Joel Lehman, Jay Chen, Jeff Clune, Kenneth O. Stanley
mathjax: true
---

* content
{:toc}

##### Abstract
While neuroevolution (evolving neural networks) has a successful track record across a variety of domains from reinforcement learning to artificial life, it is rarely applied to large, deep neural networks. A central reason is that while random mutation generally works in low dimensions, a random perturbation of thousands or millions of weights is likely to break existing functionality, providing no learning signal even if some individual weight changes were beneficial. This paper proposes a solution by introducing a family of safe mutation (SM) operators that aim within the mutation operator itself to find a degree of change that does not alter network behavior too much, but still facilitates exploration. Importantly, these SM operators do not require any additional interactions with the environment. The most effective SM variant capitalizes on the intriguing opportunity to scale the degree of mutation of each individual weight according to the sensitivity of the network's outputs to that weight, which requires computing the gradient of outputs with respect to the weights (instead of the gradient of error, as in conventional deep learning). This safe mutation through gradients (SM-G) operator dramatically increases the ability of a simple genetic algorithm-based neuroevolution method to find solutions in high-dimensional domains that require deep and/or recurrent neural networks (which tend to be particularly brittle to mutation), including domains that require processing raw pixels. By improving our ability to evolve deep neural networks, this new safer approach to mutation expands the scope of domains amenable to neuroevolution.

##### Abstract (translated by Google)
虽然神经元进化（演化神经网络）在从强化学习到人工生命的各个领域都有成功的记录，但它很少应用于大的深度神经网络。一个重要的原因是随机突变一般在低维度下工作，而数千或数百万重量的随机扰动很可能破坏现有的功能，即使某些个体体重变化是有益的，也不会提供学习信号。本文提出了一种解决方案，通过引入一组安全变异（SM）算子，以变异算子本身为目标，寻找一个不会改变网络行为的变化程度，但仍然有利于探索。重要的是，这些SM运营商不需要任何额外的与环境的交互。最有效的SM变体利用有趣的机会来根据网络的输出对该权重的敏感度来缩放每个单独权重的变化程度，这需要计算关于权重的输出的梯度（而不是梯度错误，如在传统的深度学习中）。这种通过梯度（SM-G）算子的安全突变显着增加了一种简单的基于遗传算法的神经进化方法在需要深度和/或递归神经网络的高维域中寻找解决方案的能力（其倾向于特别易于变异），包括需要处理原始像素的域。通过提高我们进化深度神经网络的能力，这种新的更安全的突变方法扩大了可用于神经进化的领域范围。

##### URL
[http://arxiv.org/abs/1712.06563](http://arxiv.org/abs/1712.06563)

##### PDF
[http://arxiv.org/pdf/1712.06563](http://arxiv.org/pdf/1712.06563)

