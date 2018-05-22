---
layout: post
title: "Learning to Search via Retrospective Imitation"
date: 2018-05-19 22:33:54
categories: arXiv_AI
tags: arXiv_AI
author: Jialin Song, Ravi Lanka, Albert Zhao, Yisong Yue, Masahiro Ono
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of learning a good search policy from demonstrations for combinatorial search spaces. We propose retrospective imitation learning, which, after initial training by an expert, improves itself by learning from its own retrospective solutions. That is, when the policy eventually reaches a feasible solution in a search tree after making mistakes and backtracks, it retrospectively constructs an improved search trace to the solution by removing backtracks, which is then used to further train the policy. A key feature of our approach is that it can iteratively scale up, or transfer, to larger problem sizes than the initial expert demonstrations. We showcase the effectiveness of our approach on a synthetic maze solving task and the problem of risk-aware path planning.

##### Abstract (translated by Google)
我们从组合搜索空间的示范来研究学习良好搜索策略的问题。我们提出回顾性模仿学习，在专家初步培训后，通过学习自己的回顾性解决方案来提高自身。也就是说，当策略在出现错误和回溯后最终在搜索树中找到可行的解决方案时，它通过去除回溯构建一个改进的解决方案搜索轨迹，然后用于进一步培训策略。我们方法的一个关键特征是它可以迭代地放大或转移，以比最初的专家演示更大的问题大小。我们展示了我们在合成迷宫解决任务方面的有效性以及风险感知路径规划问题。

##### URL
[http://arxiv.org/abs/1804.00846](http://arxiv.org/abs/1804.00846)

##### PDF
[http://arxiv.org/pdf/1804.00846](http://arxiv.org/pdf/1804.00846)

