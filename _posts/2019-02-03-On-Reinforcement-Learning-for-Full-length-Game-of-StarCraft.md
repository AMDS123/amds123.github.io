---
layout: post
title: "On Reinforcement Learning for Full-length Game of StarCraft"
date: 2019-02-03 18:00:54
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Transfer_Learning
author: Zhen-Jia Pang, Ruo-Ze Liu, Zhou-Yu Meng, Yi Zhang, Yang Yu, Tong Lu
mathjax: true
---

* content
{:toc}

##### Abstract
StarCraft II poses a grand challenge for reinforcement learning. The main difficulties of it include huge state and action space and a long-time horizon. In this paper, we investigate a hierarchical reinforcement learning approach for StarCraft II. The hierarchy involves two levels of abstraction. One is the macro-action automatically extracted from expert's trajectories, which reduces the action space in an order of magnitude yet remains effective. The other is a two-layer hierarchical architecture which is modular and easy to scale, enabling a curriculum transferring from simpler tasks to more complex tasks. The reinforcement training algorithm for this architecture is also investigated. On a 64x64 map and using restrictive units, we achieve a winning rate of more than 99\% against the difficulty level-1 built-in AI. Through the curriculum transfer learning algorithm and a mixture of combat model, we can achieve over 93\% winning rate of Protoss against the most difficult non-cheating built-in AI (level-7) of Terran, training within two days using a single machine with only 48 CPU cores and 8 K40 GPUs. It also shows strong generalization performance, when tested against never seen opponents including cheating levels built-in AI and all levels of Zerg and Protoss built-in AI. We hope this study could shed some light on the future research of large-scale reinforcement learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.09095](http://arxiv.org/abs/1809.09095)

##### PDF
[http://arxiv.org/pdf/1809.09095](http://arxiv.org/pdf/1809.09095)

