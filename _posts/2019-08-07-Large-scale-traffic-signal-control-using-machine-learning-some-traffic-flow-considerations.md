---
layout: post
title: "Large-scale traffic signal control using machine learning: some traffic flow considerations"
date: 2019-08-07 15:08:33
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Jorge A. Laval, Hao Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
This paper uses supervised learning, random search and deep reinforcement learning (DRL) methods to control large signalized intersection networks. The traffic model is Cellular Automaton rule 184, which has been shown to be a parameter-free representation of traffic flow, and is the most efficient implementation of the Kinematic Wave model with triangular fundamental diagram. We are interested in the steady-state performance of the system, both spatially and temporally: we consider a homogeneous grid network inscribed on a torus, which makes the network boundary-free, and drivers choose random routes. As a benchmark we use the longest-queue-first (LQF) greedy algorithm. We find that: (i) a policy trained with supervised learning with only two examples outperforms LQF, (ii) random search is able to generate near-optimal policies, (iii) the prevailing average network occupancy during training is the major determinant of the effectiveness of DRL policies. When trained under free-flow conditions one obtains DRL policies that are optimal for all traffic conditions, but this performance deteriorates as the occupancy during training increases. For occupancies &gt; 75% during training, DRL policies perform very poorly for all traffic conditions, which means that DRL methods cannot learn under highly congested conditions. We conjecture that DRL's inability to learn under congestion might be explained by a property of urban networks found here, whereby even a very bad policy produces an intersection throughput higher than downstream capacity. This means that the actual throughput tends to be independent of the policy. Our findings imply that it is advisable for current DRL methods in the literature to discard any congested data when training, and that doing this will improve their performance under all traffic conditions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02673](http://arxiv.org/abs/1908.02673)

##### PDF
[http://arxiv.org/pdf/1908.02673](http://arxiv.org/pdf/1908.02673)

