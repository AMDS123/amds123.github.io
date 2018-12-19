---
layout: post
title: "Continual Match Based Training in Pommerman: Technical Report"
date: 2018-12-18 11:08:31
categories: arXiv_AI
tags: arXiv_AI
author: Peng Peng, Liang Pang, Yufeng Yuan, Chao Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Continual learning is the ability of agents to improve their capacities throughout multiple tasks continually. While recent works in the literature of continual learning mostly focused on developing either particular loss functions or specialized structures of neural network explaining the episodic memory or neural plasticity, we study continual learning from the perspective of the training mechanism. Specifically, we propose a COnitnual Match BAsed Training (COMBAT) framework for training a population of advantage-actor-critic (A2C) agents in Pommerman, a partially observable multi-agent environment with no communication. Following the COMBAT framework, we trained an agent, namely, Navocado, that won the title of the top 1 learning agent in the NeurIPS 2018 Pommerman Competition. Two critical features of our agent are worth mentioning. Firstly, our agent did not learn from any demonstrations. Secondly, our agent is highly reproducible. As a technical report, we articulate the design of state space, action space, reward, and most importantly, the COMBAT framework for our Pommerman agent. We show in the experiments that Pommerman is a perfect environment for studying continual learning, and the agent can improve its performance by continually learning new skills without forgetting the old ones. Finally, the result in the Pommerman Competition verifies the robustness of our agent when competing with various opponents.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07297](http://arxiv.org/abs/1812.07297)

##### PDF
[http://arxiv.org/pdf/1812.07297](http://arxiv.org/pdf/1812.07297)

