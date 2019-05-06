---
layout: post
title: "Deep Predictive Policy Training using Reinforcement Learning"
date: 2017-03-02 11:29:57
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Ali Ghadirzadeh, Atsuto Maki, Danica Kragic, Mårten Björkman
mathjax: true
---

* content
{:toc}

##### Abstract
Skilled robot task learning is best implemented by predictive action policies due to the inherent latency of sensorimotor processes. However, training such predictive policies is challenging as it involves finding a trajectory of motor activations for the full duration of the action. We propose a data-efficient deep predictive policy training (DPPT) framework with a deep neural network policy architecture which maps an image observation to a sequence of motor activations. The architecture consists of three sub-networks referred to as the perception, policy and behavior super-layers. The perception and behavior super-layers force an abstraction of visual and motor data trained with synthetic and simulated training samples, respectively. The policy super-layer is a small sub-network with fewer parameters that maps data in-between the abstracted manifolds. It is trained for each task using methods for policy search reinforcement learning. We demonstrate the suitability of the proposed architecture and learning framework by training predictive policies for skilled object grasping and ball throwing on a PR2 robot. The effectiveness of the method is illustrated by the fact that these tasks are trained using only about 180 real robot attempts with qualitative terminal rewards.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.00727](https://arxiv.org/abs/1703.00727)

##### PDF
[https://arxiv.org/pdf/1703.00727](https://arxiv.org/pdf/1703.00727)

