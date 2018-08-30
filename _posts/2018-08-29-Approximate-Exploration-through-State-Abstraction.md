---
layout: post
title: "Approximate Exploration through State Abstraction"
date: 2018-08-29 13:41:33
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Adrien Ali Ta&#xef;ga, Aaron Courville, Marc G. Bellemare
mathjax: true
---

* content
{:toc}

##### Abstract
Although exploration in reinforcement learning is well understood from a theoretical point of view, provably correct methods remain impractical. In this paper we study the interplay between exploration and approximation, what we call \emph{approximate exploration}. We first provide results when the approximation is explicit, quantifying the performance of an exploration algorithm, MBIE-EB \citep{strehl2008analysis}, when combined with state aggregation. In particular, we show that this allows the agent to trade off between learning speed and quality of the policy learned. We then turn to a successful exploration scheme in practical, pseudo-count based exploration bonuses \citep{bellemare2016unifying}. We show that choosing a density model implicitly defines an abstraction and that the pseudo-count bonus incentivizes the agent to explore using this abstraction. We find, however, that implicit exploration may result in a mismatch between the approximated value function and exploration bonus, leading to either under- or over-exploration.

##### Abstract (translated by Google)
虽然从理论的角度很好地理解强化学习的探索，但可证明正确的方法仍然是不切实际的。在本文中，我们研究了探索和近似之间的相互作用，我们称之为\ emph {近似探索}。当近似是显式的时，我们首先提供结果，当与状态聚合结合时，量化探索算法MBIE-EB \ citep {strehl2008analysis}的性能。特别是，我们表明，这允许代理人在学习速度和所学政策的质量之间进行权衡。然后，我们转向一个成功的探索计划，在实际的，基于伪计数的探索奖金\ citep {bellemare2016unifying}。我们表明，选择密度模型隐含地定义了一个抽象，并且伪计数奖励激励代理人使用这种抽象进行探索。然而，我们发现隐式探索可能导致近似值函数和探索奖励之间的不匹配，从而导致探索不足或过度探索。

##### URL
[http://arxiv.org/abs/1808.09819](http://arxiv.org/abs/1808.09819)

##### PDF
[http://arxiv.org/pdf/1808.09819](http://arxiv.org/pdf/1808.09819)

