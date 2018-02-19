---
layout: post
title: "Monte Carlo Q-learning for General Game Playing"
date: 2018-02-16 14:18:46
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Relation
author: Hui Wang, Michael Emmerich, Aske Plaat
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the interest in reinforcement learning in game playing has been renewed. This is evidenced by the groundbreaking results achieved by AlphaGo. General Game Playing (GGP) provides a good testbed for reinforcement learning, currently one of the hottest fields of AI. In GGP, a specification of games rules is given. The description specifies a reinforcement learning problem, leaving programs to find strategies for playing well. Q-learning is one of the canonical reinforcement learning methods, which is used as baseline on some previous work (Banerjee & Stone, IJCAI 2007). We implement Q-learning in GGP for three small board games (Tic-Tac-Toe, Connect-Four, Hex). We find that Q-learning converges, and thus that this general reinforcement learning method is indeed applicable to General Game Playing. However, convergence is slow, in comparison to MCTS (a reinforcement learning method reported to achieve good results). We enhance Q-learning with Monte Carlo Search. This enhancement improves performance of pure Q-learning, although it does not yet out-perform MCTS. Future work is needed into the relation between MCTS and Q-learning, and on larger problem instances.

##### Abstract (translated by Google)
最近，玩游戏中的强化学习的兴趣已经更新。 AlphaGo取得的突破性成果证明了这一点。一般游戏玩法（GGP）为强化学习提供了一个很好的测试平台，目前它是AI最热门的领域之一。在GGP中，给出了游戏规则的规范。描述指定了一个强化学习问题，让程序找到打好的策略。 Q-learning是规范强化学习方法之一，在以前的一些工作中被用作基线（Banerjee＆Stone，IJCAI 2007）。我们在GGP中为三款小型棋盘游戏（Tic-Tac-Toe，Connect-Four，Hex）实施Q-learning。我们发现Q学习收敛，因此这种通用强化学习方法确实适用于一般游戏。然而，与MCTS相比，收敛速度较慢（据报道，强化学习方法可获得良好的结果）。我们利用蒙特卡洛搜索增强Q学习。这种增强提高了纯Q学习的性能，尽管它还没有超出MCTS。 MCTS和Q-learning之间的关系以及更大的问题实例需要将来的工作。

##### URL
[https://arxiv.org/abs/1802.05944](https://arxiv.org/abs/1802.05944)

##### PDF
[https://arxiv.org/pdf/1802.05944](https://arxiv.org/pdf/1802.05944)

