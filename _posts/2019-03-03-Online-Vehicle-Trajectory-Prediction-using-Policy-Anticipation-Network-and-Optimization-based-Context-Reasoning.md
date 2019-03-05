---
layout: post
title: "Online Vehicle Trajectory Prediction using Policy Anticipation Network and Optimization-based Context Reasoning"
date: 2019-03-03 06:54:20
categories: arXiv_RO
tags: arXiv_RO Optimization RNN Prediction
author: Wenchao Ding, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an online two-level vehicle trajectory prediction framework for urban autonomous driving where there are complex contextual factors, such as lane geometries, road constructions, traffic regulations and moving agents. Our method combines high-level policy anticipation with low-level context reasoning. We leverage a long short-term memory (LSTM) network to anticipate the vehicle's driving policy (e.g., forward, yield, turn left, turn right, etc.) using its sequential history observations. The policy is then used to guide a low-level optimization-based context reasoning process. We show that it is essential to incorporate the prior policy anticipation due to the multimodal nature of the future trajectory. Moreover, contrary to existing regression-based trajectory prediction methods, our optimization-based reasoning process can cope with complex contextual factors. The final output of the two-level reasoning process is a continuous trajectory that automatically adapts to different traffic configurations and accurately predicts future vehicle motions. The performance of the proposed framework is analyzed and validated in an emerging autonomous driving simulation platform (CARLA).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00847](http://arxiv.org/abs/1903.00847)

##### PDF
[http://arxiv.org/pdf/1903.00847](http://arxiv.org/pdf/1903.00847)

