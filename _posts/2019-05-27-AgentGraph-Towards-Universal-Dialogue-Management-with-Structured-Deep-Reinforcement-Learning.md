---
layout: post
title: "AgentGraph: Towards Universal Dialogue Management with Structured Deep Reinforcement Learning"
date: 2019-05-27 14:27:13
categories: arXiv_AI
tags: arXiv_AI Ontology Reinforcement_Learning Optimization
author: Lu Chen, Zhi Chen, Bowen Tan, Sishan Long, Milica Gasic, Kai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Dialogue policy plays an important role in task-oriented spoken dialogue systems. It determines how to respond to users. The recently proposed deep reinforcement learning (DRL) approaches have been used for policy optimization. However, these deep models are still challenging for two reasons: 1) Many DRL-based policies are not sample-efficient. 2) Most models don't have the capability of policy transfer between different domains. In this paper, we propose a universal framework, AgentGraph, to tackle these two problems. The proposed AgentGraph is the combination of GNN-based architecture and DRL-based algorithm. It can be regarded as one of the multi-agent reinforcement learning approaches. Each agent corresponds to a node in a graph, which is defined according to the dialogue domain ontology. When making a decision, each agent can communicate with its neighbors on the graph. Under AgentGraph framework, we further propose Dual GNN-based dialogue policy, which implicitly decomposes the decision in each turn into a high-level global decision and a low-level local decision. Experiments show that AgentGraph models significantly outperform traditional reinforcement learning approaches on most of the 18 tasks of the PyDial benchmark. Moreover, when transferred from the source task to a target task, these models not only have acceptable initial performance but also converge much faster on the target task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11259](https://arxiv.org/abs/1905.11259)

##### PDF
[https://arxiv.org/pdf/1905.11259](https://arxiv.org/pdf/1905.11259)

