---
layout: post
title: "Efficient Probabilistic Performance Bounds for Inverse Reinforcement Learning"
date: 2018-06-23 02:11:52
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Daniel S. Brown, Scott Niekum
mathjax: true
---

* content
{:toc}

##### Abstract
In the field of reinforcement learning there has been recent progress towards safety and high-confidence bounds on policy performance. However, to our knowledge, no practical methods exist for determining high-confidence policy performance bounds in the inverse reinforcement learning setting---where the true reward function is unknown and only samples of expert behavior are given. We propose a sampling method based on Bayesian inverse reinforcement learning that uses demonstrations to determine practical high-confidence upper bounds on the $\alpha$-worst-case difference in expected return between any evaluation policy and the optimal policy under the expert's unknown reward function. We evaluate our proposed bound on both a standard grid navigation task and a simulated driving task and achieve tighter and more accurate bounds than a feature count-based baseline. We also give examples of how our proposed bound can be utilized to perform risk-aware policy selection and risk-aware policy improvement. Because our proposed bound requires several orders of magnitude fewer demonstrations than existing high-confidence bounds, it is the first practical method that allows agents that learn from demonstration to express confidence in the quality of their learned policy.

##### Abstract (translated by Google)
在强化学习领域，最近在安全性和政策绩效的高信度方面取得了进展。但是，就我们所知，在反向强化学习设置中，没有实用的方法来确定高置信度策略的性能界限---真正的奖励函数是未知的，只给出专家行为的样本。我们提出了一种基于贝叶斯反向强化学习的抽样方法，该方法使用示例来确定任意评估策略与专家未知奖励函数下的最优策略之间的预期回报中的$ \ alpha $ -worst-case差异的实际高置信上限。我们评估了我们在标准网格导航任务和模拟驾驶任务上提出的界限，并且实现了比基于特征计数的基线更紧密和更精确的界限。我们还举例说明我们提出的约束如何被用来执行风险感知策略选择和风险感知策略改进。因为我们提出的界限要比现有的高置信界限要少好几个数量级的演示，所以这是第一个可以让演示学习的代理人对他们所学的策略的质量表示信心的实用方法。

##### URL
[http://arxiv.org/abs/1707.00724](http://arxiv.org/abs/1707.00724)

##### PDF
[http://arxiv.org/pdf/1707.00724](http://arxiv.org/pdf/1707.00724)

