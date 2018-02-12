---
layout: post
title: "Learning Robust Options"
date: 2018-02-09 12:52:06
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning
author: Daniel J. Mankowitz, Timothy A. Mann, Pierre-Luc Bacon, Doina Precup, Shie Mannor
mathjax: true
---

* content
{:toc}

##### Abstract
Robust reinforcement learning aims to produce policies that have strong guarantees even in the face of environments/transition models whose parameters have strong uncertainty. Existing work uses value-based methods and the usual primitive action setting. In this paper, we propose robust methods for learning temporally abstract actions, in the framework of options. We present a Robust Options Policy Iteration (ROPI) algorithm with convergence guarantees, which learns options that are robust to model uncertainty. We utilize ROPI to learn robust options with the Robust Options Deep Q Network (RO-DQN) that solves multiple tasks and mitigates model misspecification due to model uncertainty. We present experimental results which suggest that policy iteration with linear features may have an inherent form of robustness when using coarse feature representations. In addition, we present experimental results which demonstrate that robustness helps policy iteration implemented on top of deep neural networks to generalize over a much broader range of dynamics than non-robust policy iteration.

##### Abstract (translated by Google)
强健的强化学习旨在制定政策，即使在参数具有强烈不确定性的环境/转换模型面前，也可以提供强有力的保证。现有的工作使用基于价值的方法和通常的原始操作设置。在本文中，我们提出了在选择框架下学习时间抽象行为的鲁棒方法。我们提出了一个具有收敛保证的鲁棒选项策略迭代（ROPI）算法，该算法学习了对模型不确定性具有鲁棒性的选项。我们利用ROPI通过Robust Options Deep Q Network（RO-DQN）学习强大的选项，该解决方案可解决多项任务，并缓解由于模型不确定性导致的模型错误指定。我们提出的实验结果表明，使用粗糙特征表示时，具有线性特征的策略迭代可能具有固有形式的鲁棒性。此外，我们提出的实验结果表明，鲁棒性有助于在深度神经网络之上实施策略迭代，以比非鲁棒策略迭代更广泛的动态范围进行概括。

##### URL
[http://arxiv.org/abs/1802.03236](http://arxiv.org/abs/1802.03236)

##### PDF
[http://arxiv.org/pdf/1802.03236](http://arxiv.org/pdf/1802.03236)

