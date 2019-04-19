---
layout: post
title: "Robust Exploration with Tight Bayesian Plausibility Sets"
date: 2019-04-17 22:54:50
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning
author: Reazul H. Russel, Tianyi Gu, Marek Petrik
mathjax: true
---

* content
{:toc}

##### Abstract
Optimism about the poorly understood states and actions is the main driving force of exploration for many provably-efficient reinforcement learning algorithms. We propose optimism in the face of sensible value functions (OFVF)- a novel data-driven Bayesian algorithm to constructing Plausibility sets for MDPs to explore robustly minimizing the worst case exploration cost. The method computes policies with tighter optimistic estimates for exploration by introducing two new ideas. First, it is based on Bayesian posterior distributions rather than distribution-free bounds. Second, OFVF does not construct plausibility sets as simple confidence intervals. Confidence intervals as plausibility sets are a sufficient but not a necessary condition. OFVF uses the structure of the value function to optimize the location and shape of the plausibility set to guarantee upper bounds directly without necessarily enforcing the requirement for the set to be a confidence interval. OFVF proceeds in an episodic manner, where the duration of the episode is fixed and known. Our algorithm is inherently Bayesian and can leverage prior information. Our theoretical analysis shows the robustness of OFVF, and the empirical results demonstrate its practical promise.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08528](http://arxiv.org/abs/1904.08528)

##### PDF
[http://arxiv.org/pdf/1904.08528](http://arxiv.org/pdf/1904.08528)

