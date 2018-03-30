---
layout: post
title: "History-aware Autonomous Exploration in Confined Environments using MAVs"
date: 2018-03-28 12:29:47
categories: arXiv_RO
tags: arXiv_RO
author: Christian Witting, Marius Fehr, Rik Bähnemann, Helen Oleynikova, Roland Siegwart
mathjax: true
---

* content
{:toc}

##### Abstract
Many scenarios require a robot to be able to explore its 3D environment online without human supervision. This is especially relevant for inspection tasks and search and rescue missions. To solve this high-dimensional path planning problem, sampling-based exploration algorithms have proven successful. However, these do not necessarily scale well to larger environments or spaces with narrow openings. This paper presents a 3D exploration planner based on the principles of Next-Best Views (NBVs). In this approach, a Micro-Aerial Vehicle (MAV) equipped with a limited field-of-view depth sensor randomly samples its configuration space to find promising future viewpoints. In order to obtain high sampling efficiency, our planner maintains and uses a history of visited places, and locally optimizes the robot's orientation with respect to unobserved space. We evaluate our method in several simulated scenarios, and compare it against a state-of-the-art exploration algorithm. The experiments show substantial improvements in exploration time ($2\times$ faster), computation time, and path length, and advantages in handling difficult situations such as escaping dead-ends (up to $20\times$ faster). Finally, we validate the on-line capability of our algorithm on a computational constrained real world MAV.

##### Abstract (translated by Google)
许多场景需要机器人能够在没有人工监控的情况下在线探索其3D环境。这对检查任务和搜救任务特别重要。为了解决这个高维路径规划问题，基于抽样的探索算法已被证明是成功的。但是，这些不一定适合较大的环境或窄开口的空间。本文提出了基于Next-Best Views（NBV）原理的3D勘探规划器。在这种方法中，配备有限视场深度传感器的微型飞行器（MAV）随机采样其配置空间以寻找有前景的未来观点。为了获得高采样效率，我们的计划员维护并使用访问过的地点的历史记录，并针对未观测到的空间局部优化机器人的方向。我们在几个模拟场景中评估我们的方法，并将其与最先进的勘探算法进行比较。实验显示，勘探时间（$ 2 / times $更快），计算时间和路径长度等方面的实质性改进，以及在处理诸如逃避死角（高达$ 20 / times $更快）的困难情况中的优势。最后，我们验证了我们的算法在计算约束的真实世界MAV上的在线能力。

##### URL
[https://arxiv.org/abs/1803.10558](https://arxiv.org/abs/1803.10558)

##### PDF
[https://arxiv.org/pdf/1803.10558](https://arxiv.org/pdf/1803.10558)

