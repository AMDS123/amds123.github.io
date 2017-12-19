---
layout: post
title: "ES Is More Than Just a Traditional Finite-Difference Approximator"
date: 2017-12-18 18:25:35
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning Optimization Gradient_Descent
author: Joel Lehman, Jay Chen, Jeff Clune, Kenneth O. Stanley
mathjax: true
---

* content
{:toc}

##### Abstract
An evolution strategy (ES) variant recently attracted significant attention due to its surprisingly good performance at optimizing neural networks in challenging deep reinforcement learning domains. It searches directly in the parameter space of neural networks by generating perturbations to the current set of parameters, checking their performance, and moving in the direction of higher reward. The resemblance of this algorithm to a traditional finite-difference approximation of the reward gradient in parameter space naturally leads to the assumption that it is just that. However, this assumption is incorrect. The aim of this paper is to definitively demonstrate this point empirically. ES is a gradient approximator, but optimizes for a different gradient than just reward (especially when the magnitude of candidate perturbations is high). Instead, it optimizes for the average reward of the entire population, often also promoting parameters that are robust to perturbation. This difference can channel ES into significantly different areas of the search space than gradient descent in parameter space, and also consequently to networks with significantly different properties. This unique robustness-seeking property, and its consequences for optimization, are demonstrated in several domains. They include humanoid locomotion, where networks from policy gradient-based reinforcement learning are far less robust to parameter perturbation than ES-based policies that solve the same task. While the implications of such robustness and robustness-seeking remain open to further study, the main contribution of this work is to highlight that such differences indeed exist and deserve attention.

##### Abstract (translated by Google)
进化策略（ES）变体最近引起了显着的关注，因为它在挑战深层强化学习领域的优化神经网络方面表现出色的性能。它直接在神经网络的参数空间中搜索，通过产生对当前参数集的扰动，检查它们的性能，并向更高的奖励方向移动。这种算法与传统的参数空间中的回报梯度的有限差分近似相似，自然导致这样的假设。但是，这个假设是不正确的。本文的目的是凭经验明确地证明这一点。 ES是一个梯度逼近器，但是优化的梯度不同，而不仅仅是奖励（特别是当候选扰动的幅度很高时）。相反，它优化了整个人群的平均奖励，通常也促进了对干扰强大的参数。这种差异可以将ES引导到搜索空间明显不同的区域，而不是参数空间中的梯度下降，并且因此也导致具有明显不同属性的网络。这种独特的鲁棒性寻求性质及其对优化的影响在多个领域中得到证明。它们包括人形运动，其中来自基于策略梯度的强化学习的网络比基于ES的解决相同任务的策略对参数扰动的稳健性要差得多。尽管这种强健性和强健性的意义仍有待进一步研究，但这项工作的主要贡献是强调这种差异确实存在并值得关注。

##### URL
[http://arxiv.org/abs/1712.06568](http://arxiv.org/abs/1712.06568)

##### PDF
[http://arxiv.org/pdf/1712.06568](http://arxiv.org/pdf/1712.06568)

