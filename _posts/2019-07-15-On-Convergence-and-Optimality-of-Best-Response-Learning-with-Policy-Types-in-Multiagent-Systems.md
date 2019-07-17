---
layout: post
title: "On Convergence and Optimality of Best-Response Learning with Policy Types in Multiagent Systems"
date: 2019-07-15 09:30:27
categories: arXiv_AI
tags: arXiv_AI
author: Stefano V. Albrecht, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
While many multiagent algorithms are designed for homogeneous systems (i.e. all agents are identical), there are important applications which require an agent to coordinate its actions without knowing a priori how the other agents behave. One method to make this problem feasible is to assume that the other agents draw their latent policy (or type) from a specific set, and that a domain expert could provide a specification of this set, albeit only a partially correct one. Algorithms have been proposed by several researchers to compute posterior beliefs over such policy libraries, which can then be used to determine optimal actions. In this paper, we provide theoretical guidance on two central design parameters of this method: Firstly, it is important that the user choose a posterior which can learn the true distribution of latent types, as otherwise suboptimal actions may be chosen. We analyse convergence properties of two existing posterior formulations and propose a new posterior which can learn correlated distributions. Secondly, since the types are provided by an expert, they may be inaccurate in the sense that they do not predict the agents' observed actions. We provide a novel characterisation of optimality which allows experts to use efficient model checking algorithms to verify optimality of types.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06995](http://arxiv.org/abs/1907.06995)

##### PDF
[http://arxiv.org/pdf/1907.06995](http://arxiv.org/pdf/1907.06995)

