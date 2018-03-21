---
layout: post
title: "Variance Reduction for Policy Gradient with Action-Dependent Factorized Baselines"
date: 2018-03-20 03:52:04
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Cathy Wu, Aravind Rajeswaran, Yan Duan, Vikash Kumar, Alexandre M Bayen, Sham Kakade, Igor Mordatch, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Policy gradient methods have enjoyed great success in deep reinforcement learning but suffer from high variance of gradient estimates. The high variance problem is particularly exasperated in problems with long horizons or high-dimensional action spaces. To mitigate this issue, we derive a bias-free action-dependent baseline for variance reduction which fully exploits the structural form of the stochastic policy itself and does not make any additional assumptions about the MDP. We demonstrate and quantify the benefit of the action-dependent baseline through both theoretical analysis as well as numerical results, including an analysis of the suboptimality of the optimal state-dependent baseline. The result is a computationally efficient policy gradient algorithm, which scales to high-dimensional control problems, as demonstrated by a synthetic 2000-dimensional target matching task. Our experimental results indicate that action-dependent baselines allow for faster learning on standard reinforcement learning benchmarks and high-dimensional hand manipulation and synthetic tasks. Finally, we show that the general idea of including additional information in baselines for improved variance reduction can be extended to partially observed and multi-agent tasks.

##### Abstract (translated by Google)
政策梯度方法在深度强化学习方面取得了巨大成功，但倾向于高梯度估计方差。高分辨率问题在长视野或高空动作空间的问题上特别激烈。为了缓解这个问题，我们推导出一个无偏差的基于动作的降低方差的基线，它充分利用了随机策略本身的结构形式，并且没有对MDP做任何额外的假设。我们通过理论分析和数值结果来证明和量化依赖于行动的基线的益处，包括对最佳状态依赖基线的次优性的分析。结果是计算有效的策略梯度算法，该算法可以扩展到高维控制问题，如合成的2000维目标匹配任务所证明的那样。我们的实验结果表明，依赖于行为的基线允许在标准强化学习基准和高维手动操作和综合任务上更快地学习。最后，我们表明，在基线中包含额外信息以改进方差减少的总体思路可以扩展到部分观察和多代理任务。

##### URL
[http://arxiv.org/abs/1803.07246](http://arxiv.org/abs/1803.07246)

##### PDF
[http://arxiv.org/pdf/1803.07246](http://arxiv.org/pdf/1803.07246)

