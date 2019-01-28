---
layout: post
title: "Distributed Policy Iteration for Scalable Approximation of Cooperative Multi-Agent Policies"
date: 2019-01-25 07:13:29
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Recommendation
author: Thomy Phan, Kyrill Schmid, Lenz Belzner, Thomas Gabor, Sebastian Feld, Claudia Linnhoff-Popien
mathjax: true
---

* content
{:toc}

##### Abstract
Decision making in multi-agent systems (MAS) is a great challenge due to enormous state and joint action spaces as well as uncertainty, making centralized control generally infeasible. Decentralized control offers better scalability and robustness but requires mechanisms to coordinate on joint tasks and to avoid conflicts. Common approaches to learn decentralized policies for cooperative MAS suffer from non-stationarity and lacking credit assignment, which can lead to unstable and uncoordinated behavior in complex environments. In this paper, we propose Strong Emergent Policy approximation (STEP), a scalable approach to learn strong decentralized policies for cooperative MAS with a distributed variant of policy iteration. For that, we use function approximation to learn from action recommendations of a decentralized multi-agent planning algorithm. STEP combines decentralized multi-agent planning with centralized learning, only requiring a generative model for distributed black box optimization. We experimentally evaluate STEP in two challenging and stochastic domains with large state and joint action spaces and show that STEP is able to learn stronger policies than standard multi-agent reinforcement learning algorithms, when combining multi-agent open-loop planning with centralized function approximation. The learned policies can be reintegrated into the multi-agent planning process to further improve performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08761](http://arxiv.org/abs/1901.08761)

##### PDF
[http://arxiv.org/pdf/1901.08761](http://arxiv.org/pdf/1901.08761)

