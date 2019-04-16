---
layout: post
title: "Learning to Guide: Guidance Law Based on Deep Meta-learning and Model Predictive Path Integral Control"
date: 2019-04-15 07:47:35
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Chen Liang, Weihong Wang, Zhenghua Liu, Chao Lai, Benchun Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel guidance scheme based on model-based deep reinforcement learning (RL) technique. With model-based deep RL method, a deep neural network is trained as a predictive model of guidance dynamics which is incorporated into a model predictive path integral (MPPI) control framework. However the traditional MPPI framework assumes the actual environment similar to the training dataset for the deep neural network which is impractical in practice with different maneuvering of target, other perturbations and actuator failures. To address this problem, our method utilize meta-learning technique to make the deep neural dynamics model adapt to such changes online. With this approach we can alleviate the performance deterioration of standard MPPI control caused by the difference between actual environment and training data. Then, a novel guidance law for a varying velocity interceptor intercepting maneuvering target with desired terminal impact angle under actuator failure is constructed based on aforementioned techniques. Simulation and experiment results under different cases show the effectiveness and robustness of the proposed guidance law in achieving successful interceptions of maneuvering target.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06892](http://arxiv.org/abs/1904.06892)

##### PDF
[http://arxiv.org/pdf/1904.06892](http://arxiv.org/pdf/1904.06892)

