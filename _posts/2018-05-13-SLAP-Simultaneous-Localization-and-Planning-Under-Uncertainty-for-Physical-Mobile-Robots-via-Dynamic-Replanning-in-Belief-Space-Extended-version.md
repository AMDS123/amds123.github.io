---
layout: post
title: "SLAP: Simultaneous Localization and Planning Under Uncertainty for Physical Mobile Robots via Dynamic Replanning in Belief Space: Extended version"
date: 2018-05-13 01:15:47
categories: arXiv_RO
tags: arXiv_RO
author: Ali-akbar Agha-mohammadi, Saurav Agarwal, Sung-Kyun Kim, Suman Chakravorty, Nancy M. Amato
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous localization and Planning (SLAP) is a crucial ability for an autonomous robot operating under uncertainty. In its most general form, SLAP induces a continuous POMDP (partially-observable Markov decision process), which needs to be repeatedly solved online. This paper addresses this problem and proposes a dynamic replanning scheme in belief space. The underlying POMDP, which is continuous in state, action, and observation space, is approximated offline via sampling-based methods, but operates in a replanning loop online to admit local improvements to the coarse offline policy. This construct enables the proposed method to combat changing environments and large localization errors, even when the change alters the homotopy class of the optimal trajectory. It further outperforms the state-of-the-art FIRM (Feedback-based Information RoadMap) method by eliminating unnecessary stabilization steps. Applying belief space planning to physical systems brings with it a plethora of challenges. A key focus of this paper is to implement the proposed planner on a physical robot and show the SLAP solution performance under uncertainty, in changing environments and in the presence of large disturbances, such as a kidnapped robot situation.

##### Abstract (translated by Google)
同时定位和规划（SLAP）对于在不确定情况下运行的自主机器人是至关重要的能力。在最通用的形式中，SLAP引发连续的POMDP（部分可观察的马尔可夫决策过程），需要在线重复解决。本文针对这个问题提出了一个信念空间中的动态重新规划方案。在状态，行动和观察空间中连续的底层POMDP通过基于抽样的方法进行离线逼近，但是在线重新规划循环中运行以承认本地对粗略离线策略的改进。该构造使得所提出的方法能够对抗变化的环境和大的定位误差，即使当变化改变了最优轨迹的同伦类时。通过消除不必要的稳定步骤，它进一步优于最先进的FIRM（基于反馈的信息路线图）方法。将信仰空间规划应用于物理系统带来了诸多挑战。本文的一个重点是在物理机器人上实现提议的规划器，并在不确定性，变化的环境中以及存在大型干扰（如被绑架的机器人情况）时展示SLAP解决方案的性能。

##### URL
[http://arxiv.org/abs/1510.07380](http://arxiv.org/abs/1510.07380)

##### PDF
[http://arxiv.org/pdf/1510.07380](http://arxiv.org/pdf/1510.07380)

