---
layout: post
title: "Deep Reinforcement Learning for Swarm Systems"
date: 2019-06-06 10:27:01
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Embedding
author: Maximilian H&#xfc;ttenrauch, Adrian &#x160;o&#x161;i&#x107;, Gerhard Neumann
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep reinforcement learning (RL) methods have been applied successfully to multi-agent scenarios. Typically, these methods rely on a concatenation of agent states to represent the information content required for decentralized decision making. However, concatenation scales poorly to swarm systems with a large number of homogeneous agents as it does not exploit the fundamental properties inherent to these systems: (i) the agents in the swarm are interchangeable and (ii) the exact number of agents in the swarm is irrelevant. Therefore, we propose a new state representation for deep multi-agent RL based on mean embeddings of distributions. We treat the agents as samples of a distribution and use the empirical mean embedding as input for a decentralized policy. We define different feature spaces of the mean embedding using histograms, radial basis functions and a neural network learned end-to-end. We evaluate the representation on two well known problems from the swarm literature (rendezvous and pursuit evasion), in a globally and locally observable setup. For the local setup we furthermore introduce simple communication protocols. Of all approaches, the mean embedding representation using neural network features enables the richest information exchange between neighboring agents facilitating the development of more complex collective strategies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.06613](http://arxiv.org/abs/1807.06613)

##### PDF
[http://arxiv.org/pdf/1807.06613](http://arxiv.org/pdf/1807.06613)

