---
layout: post
title: "MoËT: Interpretable and Verifiable Reinforcement Learning via Mixture of Expert Trees"
date: 2019-06-16 15:28:35
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Marko Vasic, Andrija Petrovic, Kaiyuan Wang, Mladen Nikolic, Rishabh Singh, Sarfraz Khurshid
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Reinforcement Learning (DRL) has led to many recent breakthroughs on complex control tasks, such as defeating the best human player in the game of Go. However, decisions made by the DRL agent are not explainable, hindering its applicability in safety-critical settings. Viper, a recently proposed technique, constructs a decision tree policy by mimicking the DRL agent. Decision trees are interpretable as each action made can be traced back to the decision rule path that lead to it. However, one global decision tree approximating the DRL policy has significant limitations with respect to the geometry of decision boundaries. We propose MoËT, a more expressive, yet still interpretable model based on Mixture of Experts, consisting of a gating function that partitions the state space, and multiple decision tree experts that specialize on different partitions. We propose a training procedure to support non-differentiable decision tree experts and integrate it into imitation learning procedure of Viper. We evaluate our algorithm on four OpenAI gym environments, and show that the policy constructed in such a way is more performant and better mimics the DRL agent by lowering mispredictions and increasing the reward. We also show that MoËT policies are amenable for verification using off-the-shelf automated theorem provers such as Z3.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06717](https://arxiv.org/abs/1906.06717)

##### PDF
[https://arxiv.org/pdf/1906.06717](https://arxiv.org/pdf/1906.06717)

