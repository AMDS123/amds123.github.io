---
layout: post
title: "Can Sophisticated Dispatching Strategy Acquired by Reinforcement Learning? - A Case Study in Dynamic Courier Dispatching System"
date: 2019-03-07 03:49:07
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Yujie Chen, Yu Qian, Yichen Yao, Zili Wu, Rongqi Li, Yinzhi Zhou, Haoyuan Hu, Yinghui Xu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study a courier dispatching problem (CDP) raised from an online pickup-service platform of Alibaba. The CDP aims to assign a set of couriers to serve pickup requests with stochastic spatial and temporal arrival rate among urban regions. The objective is to maximize the revenue of served requests given a limited number of couriers over a period of time. Many online algorithms such as dynamic matching and vehicle routing strategy from existing literature could be applied to tackle this problem. However, these methods rely on appropriately predefined optimization objectives at each decision point, which is hard in dynamic situations. This paper formulates the CDP as a Markov decision process (MDP) and proposes a data-driven approach to derive the optimal dispatching rule-set under different scenarios. Our method stacks multi-layer images of the spatial-and-temporal map and apply multi-agent reinforcement learning (MARL) techniques to evolve dispatching models. This method solves the learning inefficiency caused by traditional centralized MDP modeling. Through comprehensive experiments on both artificial dataset and real-world dataset, we show: 1) By utilizing historical data and considering long-term revenue gains, MARL achieves better performance than myopic online algorithms; 2) MARL is able to construct the mapping between complex scenarios to sophisticated decisions such as the dispatching rule. 3) MARL has the scalability to adopt in large-scale real-world scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02716](http://arxiv.org/abs/1903.02716)

##### PDF
[http://arxiv.org/pdf/1903.02716](http://arxiv.org/pdf/1903.02716)

