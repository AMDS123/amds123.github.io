---
layout: post
title: "Deep Imitative Models for Flexible Inference, Planning, and Control"
date: 2019-06-04 19:48:56
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Inference
author: Nicholas Rhinehart, Rowan McAllister, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Imitation learning is an appealing approach for autonomous control: in many tasks, demonstrations of preferred behavior can be readily obtained from human experts, removing the need for costly and potentially dangerous online data collection in the real world. However, imitation learning produces behavioral policies with limited flexibility to accommodate new goals at test-time. In contrast, model-based reinforcement learning (MBRL) can plan to arbitrary goals using a predictive dynamics model learned from data, yet suffers from two shortcomings. First, the dynamics alone cannot be used to choose desired or safe outcomes -- it estimates only what is possible, not what is preferred. Second, MBRL typically requires additional online data collection to ensure the model is accurate in situations that are actually encountered when attempting to achieve test-time goals. Collecting this data with a partially-trained model can be dangerous and time-consuming. In this paper, we propose "imitative models" to combine the benefits of imitation learning and MBRL. Imitative models are probabilistic predictive models able to plan interpretable expert-like trajectories to achieve arbitrary goals. Inference with them resembles trajectory optimization in model-based reinforcement learning, and learning them resembles imitation learning. We find this method substantially outperforms six direct imitation learning approaches (five of them prior work) and an MBRL approach in a dynamic simulated autonomous driving task, and can be learned efficiently from a fixed set of expert demonstrations without additional online data collection. We also show our model can flexibly incorporate user-supplied costs at test-time, can plan to sequences of goals, and can even perform well with imprecise goals, including goals on the wrong side of the road.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.06544](http://arxiv.org/abs/1810.06544)

##### PDF
[http://arxiv.org/pdf/1810.06544](http://arxiv.org/pdf/1810.06544)

