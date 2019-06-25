---
layout: post
title: "Reinforcement Learning with Convex Constraints"
date: 2019-06-21 21:04:27
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Sobhan Miryoosefi, Kiant&#xe9; Brantley, Hal Daum&#xe9; III, Miroslav Dudik, Robert Schapire
mathjax: true
---

* content
{:toc}

##### Abstract
In standard reinforcement learning (RL), a learning agent seeks to optimize the overall reward. However, many key aspects of a desired behavior are more naturally expressed as constraints. For instance, the designer may want to limit the use of unsafe actions, increase the diversity of trajectories to enable exploration, or approximate expert trajectories when rewards are sparse. In this paper, we propose an algorithmic scheme that can handle a wide class of constraints in RL tasks: specifically, any constraints that require expected values of some vector measurements (such as the use of an action) to lie in a convex set. This captures previously studied constraints (such as safety and proximity to an expert), but also enables new classes of constraints (such as diversity). Our approach comes with rigorous theoretical guarantees and only relies on the ability to approximately solve standard RL tasks. As a result, it can be easily adapted to work with any model-free or model-based RL. In our experiments, we show that it matches previous algorithms that enforce safety via constraints, but can also enforce new properties that these algorithms do not incorporate, such as diversity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09323](http://arxiv.org/abs/1906.09323)

##### PDF
[http://arxiv.org/pdf/1906.09323](http://arxiv.org/pdf/1906.09323)

