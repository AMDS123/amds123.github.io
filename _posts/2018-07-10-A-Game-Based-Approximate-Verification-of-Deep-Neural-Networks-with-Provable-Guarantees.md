---
layout: post
title: "A Game-Based Approximate Verification of Deep Neural Networks with Provable Guarantees"
date: 2018-07-10 11:28:46
categories: arXiv_AI
tags: arXiv_AI Adversarial Recognition
author: Min Wu, Matthew Wicker, Wenjie Ruan, Xiaowei Huang, Marta Kwiatkowska
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the improved accuracy of deep neural networks, the discovery of adversarial examples has raised serious safety concerns. In this paper, we study two variants of pointwise robustness, the maximum safe radius problem, which for a given input sample computes the minimum distance to an adversarial example, and the feature robustness problem, which aims to quantify the robustness of individual features to adversarial perturbations. We demonstrate that, under the assumption of Lipschitz continuity, both problems can be approximated using finite optimisation by discretising the input space, and the approximation has provable guarantees, i.e., the error is bounded. We then show that the resulting optimisation problems can be reduced to the solution of two-player turn-based games, where the first player selects features and the second perturbs the image within the feature. While the second player aims to minimise the distance to an adversarial example, depending on the optimisation objective the first player can be cooperative or competitive. We employ an anytime approach to solve the games, in the sense of approximating the value of a game by monotonically improving its upper and lower bounds. The Monte Carlo tree search algorithm is applied to compute upper bounds for both games, and the Admissible A* and the Alpha-Beta Pruning algorithms are, respectively, used to compute lower bounds for the maximum safety radius and feature robustness games. When working on the upper bound of the maximum safe radius problem, our tool demonstrates competitive performance against existing adversarial example crafting algorithms. Furthermore, we show how our framework can be deployed to evaluate pointwise robustness of neural networks in safety-critical applications such as traffic sign recognition in self-driving cars.

##### Abstract (translated by Google)
尽管深度神经网络的准确性得到了提高，但是对抗性实例的发现引起了严重的安全问题。在本文中，我们研究了两种变量的逐点鲁棒性，即最大安全半径问题，对于给定的输入样本计算与对抗性示例的最小距离，以及特征鲁棒性问题，其旨在量化个体特征对对抗性的鲁棒性。扰动。我们证明，在Lipschitz连续性的假设下，两个问题可以通过离散化输入空间使用有限优化来近似，并且近似具有可证明的保证，即误差是有界的。然后我们表明，由此产生的优化问题可以简化为双玩家回合制游戏的解决方案，其中第一个玩家选择功能，第二个玩家在功能中扰乱图像。虽然第二个玩家旨在最小化与对抗性示例的距离，但是根据优化目标，第一个玩家可以是合作的或竞争性的。我们采用随时随地的方法解决游戏问题，即通过单调改进游戏的上限和下限来近似游戏的价值。蒙特卡罗树搜索算法用于计算两个游戏的上界，并且允许A *和Alpha-Beta修剪算法分别用于计算最大安全半径和特征稳健性游戏的下界。当处理最大安全半径问题的上限时，我们的工具展示了针对现有对抗示例制作算法的竞争性能。此外，我们展示了如何部署我们的框架来评估神经网络在安全关键应用中的逐点鲁棒性，例如自动驾驶汽车中的交通标志识别。

##### URL
[http://arxiv.org/abs/1807.03571](http://arxiv.org/abs/1807.03571)

##### PDF
[http://arxiv.org/pdf/1807.03571](http://arxiv.org/pdf/1807.03571)

