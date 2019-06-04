---
layout: post
title: "Air Learning: An AI Research Platform for Algorithm-Hardware Benchmarking of Autonomous Aerial Robots"
date: 2019-06-02 15:20:11
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Srivatsan Krishnan, Behzad Borojerdian, William Fu, Aleksandra Faust, Vijay Janapa Reddi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Air Learning, an AI research platform for benchmarking algorithm-hardware performance and energy efficiency trade-offs. We focus in particular on deep reinforcement learning (RL) interactions in autonomous unmanned aerial vehicles (UAVs). Equipped with a random environment generator, AirLearning exposes a UAV to a diverse set of challenging scenarios. Users can specify a task, train different RL policies and evaluate their performance and energy efficiency on a variety of hardware platforms. To show how Air Learning can be used, we seed it with Deep Q Networks (DQN) and Proximal Policy Optimization (PPO) to solve a point-to-point obstacle avoidance task in three different environments, generated using our configurable environment generator. We train the two algorithms using curriculum learning and non-curriculum-learning. Air Learning assesses the trained policies' performance, under a variety of quality-of-flight (QoF) metrics, such as the energy consumed, endurance and the average trajectory length, on resource-constrained embedded platforms like a Ras-Pi. We find that the trajectories on an embedded Ras-Pi are vastly different from those predicted on a high-end desktop system, resulting in up to 79.43% longer trajectories in one of the environments. To understand the source of such differences, we use Air Learning to artificially degrade desktop performance to mimic what happens on a low-end embedded system. QoF metrics with hardware-in-the-loop characterize those differences and expose how the choice of onboard compute affects the aerial robot's performance. We also conduct reliability studies to demonstrate how Air Learning can help understand how sensor failures affect the learned policies. All put together, Air Learning enables a broad class of RL studies on UAVs. More information and code for Air Learning can be found here:~\texttt{\url{<a href="http://bit.ly/2JNAVb6">this http URL</a>}}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00421](http://arxiv.org/abs/1906.00421)

##### PDF
[http://arxiv.org/pdf/1906.00421](http://arxiv.org/pdf/1906.00421)

