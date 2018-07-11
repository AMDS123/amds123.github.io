---
layout: post
title: "CIRL: Controllable Imitative Reinforcement Learning for Vision-based Self-driving"
date: 2018-07-10 17:56:22
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning
author: Xiaodan Liang, Tairui Wang, Luona Yang, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous urban driving navigation with complex multi-agent dynamics is under-explored due to the difficulty of learning an optimal driving policy. The traditional modular pipeline heavily relies on hand-designed rules and the pre-processing perception system while the supervised learning-based models are limited by the accessibility of extensive human experience. We present a general and principled Controllable Imitative Reinforcement Learning (CIRL) approach which successfully makes the driving agent achieve higher success rates based on only vision inputs in a high-fidelity car simulator. To alleviate the low exploration efficiency for large continuous action space that often prohibits the use of classical RL on challenging real tasks, our CIRL explores over a reasonably constrained action space guided by encoded experiences that imitate human demonstrations, building upon Deep Deterministic Policy Gradient (DDPG). Moreover, we propose to specialize adaptive policies and steering-angle reward designs for different control signals (i.e. follow, straight, turn right, turn left) based on the shared representations to improve the model capability in tackling with diverse cases. Extensive experiments on CARLA driving benchmark demonstrate that CIRL substantially outperforms all previous methods in terms of the percentage of successfully completed episodes on a variety of goal-directed driving tasks. We also show its superior generalization capability in unseen environments. To our knowledge, this is the first successful case of the learned driving policy through reinforcement learning in the high-fidelity simulator, which performs better-than supervised imitation learning.

##### Abstract (translated by Google)
由于难以学习最优驾驶政策，因此对具有复杂多智能体动力学的自主城市驾驶导航进行了探索。传统的模块化管道严重依赖于手工设计的规则和预处理感知系统，而受监督的基于学习的模型受到广泛的人类经验的可访问性的限制。我们提出了一种通用且有原则的可控模仿强化学习（CIRL）方法，该方法成功地使驾驶员仅基于高保真汽车模拟器中的视觉输入实现更高的成功率。为了减轻大型连续行动空间的低勘探效率，这通常禁止在挑战性的实际任务中使用经典RL，我们的CIRL探索了一个合理约束的行动空间，该模拟体验由模仿人类示范的编码体验引导，建立在深层确定性政策梯度（DDPG）之上）。此外，我们建议基于共享表示专门针对不同控制信号（即跟随，直线，右转，左转）的自适应策略和转向角奖励设计，以提高处理不同情况的模型能力。关于CARLA驾驶基准的广泛实验表明，就各种目标导向驾驶任务成功完成的事件的百分比而言，CIRL大大优于以前的所有方法。我们还在不可见的环境中展示了其卓越的泛化能力。据我们所知，这是学习驾驶政策的第一个成功案例，通过高保真模拟器中的强化学习，其表现优于监督模仿学习。

##### URL
[http://arxiv.org/abs/1807.03776](http://arxiv.org/abs/1807.03776)

##### PDF
[http://arxiv.org/pdf/1807.03776](http://arxiv.org/pdf/1807.03776)

