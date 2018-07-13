---
layout: post
title: "Visual Reinforcement Learning with Imagined Goals"
date: 2018-07-12 17:51:16
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Represenation_Learning
author: Ashvin Nair, Vitchyr Pong, Murtaza Dalal, Shikhar Bahl, Steven Lin, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
For an autonomous agent to fulfill a wide range of user-specified goals at test time, it must be able to learn broadly applicable and general-purpose skill repertoires. Furthermore, to provide the requisite level of generality, these skills must handle raw sensory input such as images. In this paper, we propose an algorithm that acquires such general-purpose skills by combining unsupervised representation learning and reinforcement learning of goal-conditioned policies. Since the particular goals that might be required at test-time are not known in advance, the agent performs a self-supervised "practice" phase where it imagines goals and attempts to achieve them. We learn a visual representation with three distinct purposes: sampling goals for self-supervised practice, providing a structured transformation of raw sensory inputs, and computing a reward signal for goal reaching. We also propose a retroactive goal relabeling scheme to further improve the sample-efficiency of our method. Our off-policy algorithm is efficient enough to learn policies that operate on raw image observations and goals for a real-world robotic system, and substantially outperforms prior techniques.

##### Abstract (translated by Google)
对于自主代理在测试时满足用户指定的各种目标，它必须能够学习广泛适用的和通用的技能组合。此外，为了提供必要的通用性，这些技能必须处理诸如图像之类的原始感官输入。在本文中，我们提出了一种算法，通过将无监督表示学习与目标条件策略的强化学习相结合来获得这种通用技能。由于在测试时可能需要的特定目标不是事先知道的，因此代理执行自我监督的“实践”阶段，在此阶段，它想象目标并尝试实现目标。我们学习具有三个不同目的的视觉表示：自我监督实践的抽样目标，提供原始感官输入的结构化转换，以及计算目标到达的奖励信号。我们还提出了一种追溯目标重新贴标签方案，以进一步提高我们方法的样本效率。我们的非政策算法足够有效，可以学习对原始图像观察和现实世界机器人系统目标进行操作的策略，并且大大优于现有技术。

##### URL
[http://arxiv.org/abs/1807.04742](http://arxiv.org/abs/1807.04742)

##### PDF
[http://arxiv.org/pdf/1807.04742](http://arxiv.org/pdf/1807.04742)

