---
layout: post
title: "GPU-Accelerated Robotic Simulation for Distributed Reinforcement Learning"
date: 2018-10-12 23:48:09
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Jacky Liang, Viktor Makoviychuk, Ankur Handa, Nuttapong Chentanez, Miles Macklin, Dieter Fox
mathjax: true
---

* content
{:toc}

##### Abstract
Most Deep Reinforcement Learning (Deep RL) algorithms require a prohibitively large number of training samples for learning complex tasks. Many recent works on speeding up Deep RL have focused on distributed training and simulation. While distributed training is often done on the GPU, simulation is not. In this work, we propose using GPU-accelerated RL simulations as an alternative to CPU ones. Using NVIDIA Flex, a GPU-based physics engine, we show promising speed-ups of learning various continuous-control, locomotion tasks. With one GPU and CPU core, we are able to train the Humanoid running task in less than 20 minutes, using 10-1000x fewer CPU cores than previous works. We also demonstrate the scalability of our simulator to multi-GPU settings to train more challenging locomotion tasks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05762](https://arxiv.org/abs/1810.05762)

##### PDF
[https://arxiv.org/pdf/1810.05762](https://arxiv.org/pdf/1810.05762)

