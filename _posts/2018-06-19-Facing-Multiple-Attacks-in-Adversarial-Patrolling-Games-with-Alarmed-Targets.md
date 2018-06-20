---
layout: post
title: "Facing Multiple Attacks in Adversarial Patrolling Games with Alarmed Targets"
date: 2018-06-19 08:57:03
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Giuseppe De Nittis, Nicola Gatti
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on adversarial patrolling games on arbitrary graphs, where the Defender can control a mobile resource, the targets are alarmed by an alarm system, and the Attacker can observe the actions of the mobile resource of the Defender and perform different attacks exploiting multiple resources. This scenario can be modeled as a zero-sum extensive-form game in which each player can play multiple times. The game tree is exponentially large both in the size of the graph and in the number of attacking resources. We show that when the number of the Attacker's resources is free, the problem of computing the equilibrium path is NP-hard, while when the number of resources is fixed, the equilibrium path can be computed in poly-time. We provide a dynamic-programming algorithm that, given the number of the Attacker's resources, computes the equilibrium path requiring poly-time in the size of the graph and exponential time in the number of the resources. Furthermore, since in real-world scenarios it is implausible that the Defender knows the number of attacking resources, we study the robustness of the Defender's strategy when she makes a wrong guess about that number. We show that even the error of just a single resource can lead to an arbitrary inefficiency, when the inefficiency is defined as the ratio of the Defender's utilities obtained with a wrong guess and a correct guess. However, a more suitable definition of inefficiency is given by the difference of the Defender's utilities: this way, we observe that the higher the error in the estimation, the higher the loss for the Defender. Then, we investigate the performance of online algorithms when no information about the Attacker's resources is available. Finally, we resort to randomized online algorithms showing that we can obtain a competitive factor that is twice better than the one that can be achieved by any deterministic online algorithm.

##### Abstract (translated by Google)
我们专注于任意图形上的敌对巡逻游戏，其中Defender可以控制移动资源，目标受到警报系统的警报，攻击者可以观察Defender的移动资源的行为并利用多种资源执行不同的攻击。这个场景可以被模拟成一个零和广泛形式的游戏，其中每个玩家可以玩多次。无论是图的大小还是攻击资源的数量，游戏树都呈指数级增长。我们证明，当攻击者的资源数量是免费的时，计算均衡路径的问题是NP难度，而当资源数量固定时，可以在多时间内计算均衡路径。我们提供了一种动态规划算法，在给定攻击者资源的数量的情况下，计算平衡路径，需要图中的多时间和资源数量的指数时间。此外，由于在现实世界中，Defender知道攻击资源的数量并不合理，因此我们在对Defender的策略进行错误猜测时，研究了Defender策略的稳健性。我们表明即使是单一资源的错误也可能导致任意的低效率，当低效率被定义为防御者的实用程序与错误的猜测和正确的猜测得到的比率。然而，更为合适的低效率定义是由Defender的效用差异给出的：这样，我们观察到估计误差越高，Defender的损失就越高。然后，当没有关于攻击者资源的信息可用时，我们调查在线算法的性能。最后，我们求助于随机在线算法，表明我们可以获得比任何确定性在线算法所能达到的要好两倍的竞争因子。

##### URL
[http://arxiv.org/abs/1806.07111](http://arxiv.org/abs/1806.07111)

##### PDF
[http://arxiv.org/pdf/1806.07111](http://arxiv.org/pdf/1806.07111)

