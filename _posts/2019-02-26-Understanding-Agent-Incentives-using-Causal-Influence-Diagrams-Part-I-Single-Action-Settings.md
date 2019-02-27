---
layout: post
title: "Understanding Agent Incentives using Causal Influence Diagrams, Part I: Single Action Settings"
date: 2019-02-26 14:54:09
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Tom Everitt, Pedro A. Ortega, Elizabeth Barnes, Shane Legg
mathjax: true
---

* content
{:toc}

##### Abstract
Agents are systems that optimize an objective function in an environment. Together, the goal and the environment induce secondary objectives, incentives. Modeling the agent-environment interaction in graphical models called influence diagrams, we can answer two fundamental questions about an agent's incentives directly from the graph: (1) which nodes is the agent incentivized to observe, and (2) which nodes is the agent incentivized to influence? The answers tell us which information and influence points need extra protection. For example, we may want a classifier for job applications to not use the ethnicity of the candidate, and a reinforcement learning agent not to take direct control of its reward mechanism. Different algorithms and training paradigms can lead to different influence diagrams, so our method can be used to identify algorithms with problematic incentives and help in designing algorithms with better incentives.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09980](http://arxiv.org/abs/1902.09980)

##### PDF
[http://arxiv.org/pdf/1902.09980](http://arxiv.org/pdf/1902.09980)

