---
layout: post
title: "Deep-Learned Collision Avoidance Policy for Distributed Multi-Agent Navigation"
date: 2017-07-06 07:41:45
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Pinxin Long, Wenxi Liu, Jia Pan
mathjax: true
---

* content
{:toc}

##### Abstract
High-speed, low-latency obstacle avoidance that is insensitive to sensor noise is essential for enabling multiple decentralized robots to function reliably in cluttered and dynamic environments. While other distributed multi-agent collision avoidance systems exist, these systems require online geometric optimization where tedious parameter tuning and perfect sensing are necessary. We present a novel end-to-end framework to generate reactive collision avoidance policy for efficient distributed multi-agent navigation. Our method formulates an agent's navigation strategy as a deep neural network mapping from the observed noisy sensor measurements to the agent's steering commands in terms of movement velocity. We train the network on a large number of frames of collision avoidance data collected by repeatedly running a multi-agent simulator with different parameter settings. We validate the learned deep neural network policy in a set of simulated and real scenarios with noisy measurements and demonstrate that our method is able to generate a robust navigation strategy that is insensitive to imperfect sensing and works reliably in all situations. We also show that our method can be well generalized to scenarios that do not appear in our training data, including scenes with static obstacles and agents with different sizes. Videos are available at this https URL

##### Abstract (translated by Google)
对传感器噪声不敏感的高速，低延迟障碍避免对于使多个分散式机器人在混乱和动态环境中可靠运行至关重要。当存在其他分布式多智能体碰撞避免系统时，这些系统需要在线几何优化，其中繁琐的参数调整和完善的感测是必要的。我们提出了一种新颖的端到端框架，为高效的分布式多代理导航生成反应式避免碰撞策略。我们的方法将代理的导航策略制定为从观察到的噪声传感器测量到代理的转向命令在运动速度方面的深度神经网络映射。我们通过反复运行具有不同参数设置的多智能体模拟器收集的大量避碰数据帧对网络进行训练。我们验证了深度神经网络策略的一套模拟和真实的场景与噪音测量，并证明我们的方法是能够产生一个鲁棒的导航策略，是不敏感的不完善的感应，并在所有情况下可靠地工作。我们还表明，我们的方法可以很好地推广到未出现在我们的训练数据中的场景，包括具有静态障碍的场景和不同大小的代理。这个https网址提供了视频

##### URL
[https://arxiv.org/abs/1609.06838](https://arxiv.org/abs/1609.06838)

##### PDF
[https://arxiv.org/pdf/1609.06838](https://arxiv.org/pdf/1609.06838)

