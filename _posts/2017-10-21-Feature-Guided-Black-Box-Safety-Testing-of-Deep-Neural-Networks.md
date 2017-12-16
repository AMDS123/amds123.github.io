---
layout: post
title: "Feature-Guided Black-Box Safety Testing of Deep Neural Networks"
date: 2017-10-21 22:20:06
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Object_Detection Knowledge Optimization Detection Recognition
author: Matthew Wicker, Xiaowei Huang, Marta Kwiatkowska
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the improved accuracy of deep neural networks, the discovery of adversarial examples has raised serious safety concerns. Most existing approaches for crafting adversarial examples necessitate some knowledge (architecture, parameters, etc) of the network at hand. In this paper, we focus on image classifiers and propose a feature-guided black-box approach to test the safety of deep neural networks that requires no such knowledge. Our algorithm employs object detection techniques such as SIFT (Scale Invariant Feature Transform) to extract features from an image. These features are converted into a mutable saliency distribution, where high probability is assigned to pixels that affect com- position of the image with respect to the human visual system. We formulate the crafting of adversarial examples as a two-player turn-based stochastic game, where the first player's objective is to find an adversarial example by manipulating the features, and the second player can be cooperative, adversarial, or random. We show that, theoretically, the two-player game can converge to the optimal strategy, and that the optimal strategy represents a globally minimal adversarial image. Using Monte Carlo tree search we gradually explore the game state space to search for adversarial examples. Our experiments show that, despite the black- box setting, manipulations guided by a perception-based saliency distribution are competitive with state-of-the-art methods that rely on white-box saliency matrices or sophisticated optimization procedures. Finally, we show how our method can be used to evaluate robustness of neural networks in safety-critical applications such as traffic sign recognition in self-driving cars.

##### Abstract (translated by Google)
尽管深度神经网络的准确性有所提高，但敌对事例的发现引起了严重的安全问题。大多数现有的制定敌对案例的方法都需要手头网络的一些知识（架构，参数等）。在本文中，我们专注于图像分类器，并提出了一个功能引导的黑盒方法来测试深度神经网络的安全性，不需要这种知识。我们的算法采用SIFT（尺度不变特征变换）等对象检测技术从图像中提取特征。这些特征被转换成可变的显着性分布，其中将高概率分配给影响图像相对于人类视觉系统的成分的像素。我们把对手的例子制作成一个双人回合的随机博弈，其中第一个玩家的目标是通过操纵特征来找到一个敌对的例子，第二个玩家可以是合作的，敌对的或随机的。我们证明，在理论上，双人游戏可以收敛到最优策略，而最优策略代表一个全局最小的敌对图像。使用蒙特卡洛树搜索，我们逐渐探索游戏状态空间来寻找敌对的例子。我们的实验表明，尽管黑箱设置，基于感知的显着性分布指导下的操作与依赖白盒显着性矩阵或复杂的优化过程的最先进的方法是竞争的。最后，我们展示了如何使用我们的方法来评估神经网络在安全关键应用中的鲁棒性，例如自驾车中的交通标志识别。

##### URL
[https://arxiv.org/abs/1710.07859](https://arxiv.org/abs/1710.07859)

##### PDF
[https://arxiv.org/pdf/1710.07859](https://arxiv.org/pdf/1710.07859)

