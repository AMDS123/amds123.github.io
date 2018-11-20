---
layout: post
title: "Modelling the Dynamic Joint Policy of Teammates with Attention Multi-agent DDPG"
date: 2018-11-13 11:30:29
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning
author: Hangyu Mao, Zhengchao Zhang, Zhen Xiao, Zhibo Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Modelling and exploiting teammates' policies in cooperative multi-agent systems have long been an interest and also a big challenge for the reinforcement learning (RL) community. The interest lies in the fact that if the agent knows the teammates' policies, it can adjust its own policy accordingly to arrive at proper cooperations; while the challenge is that the agents' policies are changing continuously due to they are learning concurrently, which imposes difficulty to model the dynamic policies of teammates accurately. In this paper, we present \emph{ATTention Multi-Agent Deep Deterministic Policy Gradient} (ATT-MADDPG) to address this challenge. ATT-MADDPG extends DDPG, a single-agent actor-critic RL method, with two special designs. First, in order to model the teammates' policies, the agent should get access to the observations and actions of teammates. ATT-MADDPG adopts a centralized critic to collect such information. Second, to model the teammates' policies using the collected information in an effective way, ATT-MADDPG enhances the centralized critic with an attention mechanism. This attention mechanism introduces a special structure to explicitly model the dynamic joint policy of teammates, making sure that the collected information can be processed efficiently. We evaluate ATT-MADDPG on both benchmark tasks and the real-world packet routing tasks. Experimental results show that it not only outperforms the state-of-the-art RL-based methods and rule-based methods by a large margin, but also achieves better performance in terms of scalability and robustness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07029](http://arxiv.org/abs/1811.07029)

##### PDF
[http://arxiv.org/pdf/1811.07029](http://arxiv.org/pdf/1811.07029)

