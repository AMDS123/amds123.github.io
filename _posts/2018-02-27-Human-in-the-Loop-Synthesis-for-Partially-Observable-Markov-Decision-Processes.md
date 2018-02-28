---
layout: post
title: "Human-in-the-Loop Synthesis for Partially Observable Markov Decision Processes"
date: 2018-02-27 10:29:56
categories: arXiv_AI
tags: arXiv_AI Quantitative
author: Steven Carr, Nils Jansen, Ralf Wimmer, Jie Fu, Ufuk Topcu
mathjax: true
---

* content
{:toc}

##### Abstract
We study planning problems where autonomous agents operate inside environments that are subject to uncertainties and not fully observable. Partially observable Markov decision processes (POMDPs) are a natural formal model to capture such problems. Because of the potentially huge or even infinite belief space in POMDPs, synthesis with safety guarantees is, in general, computationally intractable. We propose an approach that aims to circumvent this difficulty: in scenarios that can be partially or fully simulated in a virtual environment, we actively integrate a human user to control an agent. While the user repeatedly tries to safely guide the agent in the simulation, we collect data from the human input. Via behavior cloning, we translate the data into a strategy for the POMDP. The strategy resolves all nondeterminism and non-observability of the POMDP, resulting in a discrete-time Markov chain (MC). The efficient verification of this MC gives quantitative insights into the quality of the inferred human strategy by proving or disproving given system specifications. For the case that the quality of the strategy is not sufficient, we propose a refinement method using counterexamples presented to the human. Experiments show that by including humans into the POMDP verification loop we improve the state of the art by orders of magnitude in terms of scalability.

##### Abstract (translated by Google)
我们研究了自主代理在易受不确定性和不可完全观察的环境中运行的规划问题。部分可观察的马尔可夫决策过程（POMDPs）是捕捉这些问题的自然形式模型。由于POMDP中潜在的巨大甚至是无限的信念空间，合成与安全保证一般来说在计算上是难以处理的。我们提出了一种旨在规避这一困难的方法：在可以在虚拟环境中部分或完全模拟的场景中，我们积极地集成人类用户来控制代理。在用户反复尝试在模拟中安全地引导代理时，我们从人员输入中收集数据。通过行为克隆，我们将数据转化为POMDP的策略。该策略解决了POMDP的所有不确定性和不可观测性，导致离散时间马尔可夫链（MC）。这个MC的有效验证通过证明或反驳给定的系统规格，提供了对推断人类策略质量的定量分析。对于战略质量不足的情况，我们提出一种使用反例提供给人类的改进方法。实验表明，通过将人类纳入POMDP验证循环，我们可以在可扩展性方面提高数量级。

##### URL
[http://arxiv.org/abs/1802.09810](http://arxiv.org/abs/1802.09810)

##### PDF
[http://arxiv.org/pdf/1802.09810](http://arxiv.org/pdf/1802.09810)

