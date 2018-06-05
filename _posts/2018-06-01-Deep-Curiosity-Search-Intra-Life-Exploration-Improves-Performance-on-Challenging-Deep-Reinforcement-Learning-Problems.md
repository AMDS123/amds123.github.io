---
layout: post
title: "Deep Curiosity Search: Intra-Life Exploration Improves Performance on Challenging Deep Reinforcement Learning Problems"
date: 2018-06-01 22:09:51
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Relation
author: Christopher Stanton, Jeff Clune
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional exploration methods in RL require agents to perform random actions to find rewards. But these approaches struggle on sparse-reward domains like Montezuma's Revenge where the probability that any random action sequence leads to reward is extremely low. Recent algorithms have performed well on such tasks by encouraging agents to visit new states or perform new actions in relation to all prior training episodes (which we call across-training novelty). But such algorithms do not consider whether an agent exhibits intra-life novelty: doing something new within the current episode, regardless of whether those behaviors have been performed in previous episodes. We hypothesize that across-training novelty might discourage agents from revisiting initially non-rewarding states that could become important stepping stones later in training. We introduce Deep Curiosity Search (DeepCS), which encourages intra-life exploration by rewarding agents for visiting as many different states as possible within each episode, and show that DeepCS matches the performance of current state-of-the-art methods on Montezuma's Revenge. We further show that DeepCS improves exploration on Gravitar (another difficult, sparse-reward game) and performs well on the dense-reward game Amidar. Surprisingly, DeepCS doubles A2C performance on Seaquest, a game we would not have expected to benefit from intra-life exploration because the arena is small and already easily navigated by naive exploration techniques. In one run, DeepCS achieves a maximum training score of 80,000 points on Seaquest, higher than any methods other than Ape-X. The strong performance of DeepCS on these sparse- and dense-reward tasks suggests that encouraging intra-life novelty is an interesting, new approach for improving performance in Deep RL and motivates further research into hybridizing across-training and intra-life exploration methods.

##### Abstract (translated by Google)
RL中的传统探索方法要求代理人执行随机操作来寻找奖励。但是这些方法在稀缺奖励领域挣扎，比如蒙特祖马的复仇，其中任何随机动作序列导致奖励的概率非常低。最近的算法通过鼓励代理访问新的状态或执行与所有之前的训练集（我们称之为跨训练新颖性）有关的新操作，在这些任务上表现良好。但是这样的算法并没有考虑代理人是否表现出生活中的新颖性：在当前情节中做一些新的事情，不管这些行为是否在以前的情节中都被执行过。我们假设跨训练的新颖性可能会阻止代理人重新审视最初没有奖励的国家，这些国家可能会在培训后成为重要的垫脚石。我们推出深度好奇搜索（DeepCS），它通过奖励代理商在每集中访问尽可能多的不同状态，鼓励进行内部探索，并展示DeepCS与当前最先进的蒙特苏马复仇方法的性能相匹配。我们进一步表明DeepCS改进了对Gravitar（另一个困难的，稀疏奖励游戏）的探索，并且在密集奖励游戏Amidar上表现良好。令人惊讶的是，DeepCS在Seaquest上提升了A2C性能，这是一款我们不希望从内部生命探索中受益的游戏，因为这个游戏体积很小，并且已经很容易通过天真的探索技术进行导航。在一次运行中，DeepCS在Seaquest上获得80,000点的最高训练分数，高于除Ape-X以外的任何其他方法。 DeepCS在这些稀疏和密集奖励任务上的强大表现表明，鼓励生命中新奇是一种有趣的新方法，用于提高Deep RL的表现，并促进进一步研究混合跨训练和生活内探索方法。

##### URL
[http://arxiv.org/abs/1806.00553](http://arxiv.org/abs/1806.00553)

##### PDF
[http://arxiv.org/pdf/1806.00553](http://arxiv.org/pdf/1806.00553)

