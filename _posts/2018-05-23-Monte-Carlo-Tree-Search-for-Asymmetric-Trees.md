---
layout: post
title: "Monte Carlo Tree Search for Asymmetric Trees"
date: 2018-05-23 15:19:40
categories: arXiv_AI
tags: arXiv_AI
author: Thomas M. Moerland, Joost Broekens, Aske Plaat, Catholijn M. Jonker
mathjax: true
---

* content
{:toc}

##### Abstract
We present an extension of Monte Carlo Tree Search (MCTS) that strongly increases its efficiency for trees with asymmetry and/or loops. Asymmetric termination of search trees introduces a type of uncertainty for which the standard upper confidence bound (UCB) formula does not account. Our first algorithm (MCTS-T), which assumes a non-stochastic environment, backs-up tree structure uncertainty and leverages it for exploration in a modified UCB formula. Results show vastly improved efficiency in a well-known asymmetric domain in which MCTS performs arbitrarily bad. Next, we connect the ideas about asymmetric termination to the presence of loops in the tree, where the same state appears multiple times in a single trace. An extension to our algorithm (MCTS-T+), which in addition to non-stochasticity assumes full state observability, further increases search efficiency for domains with loops as well. Benchmark testing on a set of OpenAI Gym and Atari 2600 games indicates that our algorithms always perform better than or at least equivalent to standard MCTS, and could be first-choice tree search algorithms for non-stochastic, fully-observable environments.

##### Abstract (translated by Google)
我们提出了蒙特卡洛树搜索（MCTS）的扩展，它可以极大地提高其对称和/或循环树的效率。搜索树的不对称终止引入了标准上置信区间（UCB）公式未考虑的一类不确定性。我们的第一个假设非随机环境的算法（MCTS-T）支持树结构的不确定性，并利用它在改进的UCB公式中进行探索。结果表明，在众所周知的MCTS执行任意坏的非对称域中，效率大大提高。接下来，我们将有关非对称终止的想法与树中存在的循环相关联，其中相同的状态在单个追踪中多次出现。对于我们的算法（MCTS-T +）的扩展，除了非随机性假定完全状态可观性外，还进一步提高了带有循环的域的搜索效率。在一组OpenAI Gym和Atari 2600游戏上进行基准测试表明，我们的算法总是比标准MCTS执行得更好或至少等同于标准MCTS，并且可以成为非随机，完全可观察环境的首选树搜索算法。

##### URL
[http://arxiv.org/abs/1805.09218](http://arxiv.org/abs/1805.09218)

##### PDF
[http://arxiv.org/pdf/1805.09218](http://arxiv.org/pdf/1805.09218)

