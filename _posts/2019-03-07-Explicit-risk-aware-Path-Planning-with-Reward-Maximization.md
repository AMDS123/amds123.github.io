---
layout: post
title: "Explicit-risk-aware Path Planning with Reward Maximization"
date: 2019-03-07 21:22:04
categories: arXiv_AI
tags: arXiv_AI Tracking
author: Xuesu Xiao, Jan Dufek, Robin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
This paper develops a path planner that minimizes risk (e.g. motion execution) while maximizing accumulated reward (e.g., quality of sensor viewpoint) motivated by visual assistance or tracking scenarios in unstructured or confined environments. In these scenarios, the robot should maintain the best viewpoint as it moves to the goal. However, in unstructured or confined environments, some paths may increase the risk of collision; therefore there is a tradeoff between risk and reward. Conventional state-dependent risk or probabilistic uncertainty modeling do not consider path-level risk or is difficult to acquire. This risk-reward planner explicitly represents risk as a function of motion plans, i.e., paths. Without manual assignment of the negative impact to the planner caused by risk, this planner takes in a pre-established viewpoint quality map and plans target location and path leading to it simultaneously, in order to maximize overall reward along the entire path while minimizing risk. Exact and approximate algorithms are presented, whose solution is further demonstrated on a physical tethered aerial vehicle. Other than the visual assistance problem, the proposed framework also provides a new planning paradigm to address minimum-risk planning under dynamical risk and absence of substructure optimality and to balance the trade-off between reward and risk.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03187](http://arxiv.org/abs/1903.03187)

##### PDF
[http://arxiv.org/pdf/1903.03187](http://arxiv.org/pdf/1903.03187)

