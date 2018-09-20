---
layout: post
title: "Memory Augmented Policy Optimization for Program Synthesis and Semantic Parsing"
date: 2018-09-19 07:51:12
categories: arXiv_AI
tags: arXiv_AI Sparse Weakly_Supervised Optimization
author: Chen Liang, Mohammad Norouzi, Jonathan Berant, Quoc Le, Ni Lao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents Memory Augmented Policy Optimization (MAPO): a novel policy optimization formulation that incorporates a memory buffer of promising trajectories to reduce the variance of policy gradient estimates for deterministic environments with discrete actions. The formulation expresses the expected return objective as a weighted sum of two terms: an expectation over a memory of trajectories with high rewards, and a separate expectation over the trajectories outside the memory. We propose 3 techniques to make an efficient training algorithm for MAPO: (1) distributed sampling from inside and outside memory with an actor-learner architecture; (2) a marginal likelihood constraint over the memory to accelerate training; (3) systematic exploration to discover high reward trajectories. MAPO improves the sample efficiency and robustness of policy gradient, especially on tasks with a sparse reward. We evaluate MAPO on weakly supervised program synthesis from natural language / semantic parsing tasks. On the WikiTableQuestions benchmark we improve the state-of-the-art by 2.5%, achieving an accuracy of 46.2%, and on the WikiSQL benchmark, MAPO achieves an accuracy of 74.9% with only weak supervision, outperforming several strong baselines with full supervision. Our code is open sourced at https://github.com/crazydonkey200/neural-symbolic-machines

##### Abstract (translated by Google)
本文介绍了记忆增强策略优化（MAPO）：一种新颖的策略优化公式，它包含了有前景轨迹的内存缓冲区，以减少具有离散动作的确定性环境的策略梯度估计的方差。该公式将预期回报目标表示为两个术语的加权和：对具有高回报的轨迹的记忆的期望，以及对记忆之外的轨迹的单独期望。我们提出了3种技术来为MAPO制定有效的训练算法：（1）采用演员 - 学习者架构从内部和外部分布式采样; （2）对记忆的边际可能性约束以加速训练; （3）系统探索发现高回报轨迹。 MAPO提高了样本效率和策略梯度的稳健性，特别是对于具有稀疏奖励的任务。我们从自然语言/语义分析任务中对弱监督程序综合评估MAPO。在WikiTableQuestions基准测试中，我们将最新技术水平提高了2.5％，达到了46.2％的准确率，而在WikiSQL基准测试中，MAPO仅通过弱监督就达到了74.9％的准确率，在完全监督下超越了几个强大的基线。我们的代码是开源的https://github.com/crazydonkey200/neural-symbolic-machines

##### URL
[http://arxiv.org/abs/1807.02322](http://arxiv.org/abs/1807.02322)

##### PDF
[http://arxiv.org/pdf/1807.02322](http://arxiv.org/pdf/1807.02322)

