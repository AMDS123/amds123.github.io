---
layout: post
title: "Distillation Strategies for Proximal Policy Optimization"
date: 2019-01-23 21:00:33
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning CNN Optimization Inference Deep_Learning
author: Sam Green, Craig M. Vineyard, &#xc7;etin Kaya Ko&#xe7;
mathjax: true
---

* content
{:toc}

##### Abstract
Vision-based deep reinforcement learning (RL), similar to deep learning, typically obtains a performance benefit by using high capacity and relatively large convolutional neural networks (CNN). However, a large network leads to higher inference costs (power, latency, silicon area, MAC count). Many inference optimization have been developed for CNNs. Some optimization techniques offer theoretical efficiency, but designing actual hardware to support them is difficult. On the other hand, "distillation" is a simple general-purpose optimization technique which is broadly applicable for transferring knowledge from a trained, high capacity, teacher network to an untrained, low capacity, student network. "DQN distillation" extended the original distillation idea to transfer information stored in a high performance, high capacity teacher Q-function trained via the Deep Q-Learning (DQN) algorithm. Our work adapts the DQN distillation work to the actor-critic Proximal Policy Optimization algorithm. PPO is simple to implement and has much higher performance than the seminal DQN algorithm. We show that a distilled PPO student can attain far higher performance compared to a DQN teacher. We also show that a low capacity distilled student is generally able to outperform a low capacity agent that directly trains in the environment. Finally, we show that distillation, followed by "fine-tuning" in the environment, enables the distilled PPO student to achieve parity with teacher performance. In general, the lessons learned in this work should transfer to other actor-critic RL algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08128](http://arxiv.org/abs/1901.08128)

##### PDF
[http://arxiv.org/pdf/1901.08128](http://arxiv.org/pdf/1901.08128)

