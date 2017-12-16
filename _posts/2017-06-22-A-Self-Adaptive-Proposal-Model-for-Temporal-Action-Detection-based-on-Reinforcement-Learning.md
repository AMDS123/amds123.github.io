---
layout: post
title: "A Self-Adaptive Proposal Model for Temporal Action Detection based on Reinforcement Learning"
date: 2017-06-22 10:59:33
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Detection
author: Jingjia Huang, Nannan Li, Tao Zhang, Ge Li
mathjax: true
---

* content
{:toc}

##### Abstract
Existing action detection algorithms usually generate action proposals through an extensive search over the video at multiple temporal scales, which brings about huge computational overhead and deviates from the human perception procedure. We argue that the process of detecting actions should be naturally one of observation and refinement: observe the current window and refine the span of attended window to cover true action regions. In this paper, we propose an active action proposal model that learns to find actions through continuously adjusting the temporal bounds in a self-adaptive way. The whole process can be deemed as an agent, which is firstly placed at a position in the video at random, adopts a sequence of transformations on the current attended region to discover actions according to a learned policy. We utilize reinforcement learning, especially the Deep Q-learning algorithm to learn the agent's decision policy. In addition, we use temporal pooling operation to extract more effective feature representation for the long temporal window, and design a regression network to adjust the position offsets between predicted results and the ground truth. Experiment results on THUMOS 2014 validate the effectiveness of the proposed approach, which can achieve competitive performance with current action detection algorithms via much fewer proposals.

##### Abstract (translated by Google)
现有的动作检测算法通常通过在多个时间尺度上对视频的广泛搜索来产生动作建议，这带来了巨大的计算开销并偏离了人类感知过程。我们认为，检测行为的过程当然应该是观察和细化的过程：观察当前窗口，细化出席窗口的范围以覆盖真实的行动区域。在本文中，我们提出了一个积极的行动建议模型，学习通过不断调整时间边界以自适应的方式来发现行动。整个过程可以视为一个代理，首先随机放置在视频中的一个位置，对当前就读区域进行一系列变换，根据学习策略发现动作。我们利用强化学习，特别是深度学习算法来学习代理的决策策略。另外，我们利用时间汇集操作为长时窗提取更有效的特征表示，并设计回归网络来调整预测结果与地面真实之间的位置偏移。 THUMOS 2014的实验结果验证了所提出方法的有效性，该方法可以通过少得多的方案来实现与当前动作检测算法的竞争性表现。

##### URL
[https://arxiv.org/abs/1706.07251](https://arxiv.org/abs/1706.07251)

##### PDF
[https://arxiv.org/pdf/1706.07251](https://arxiv.org/pdf/1706.07251)

