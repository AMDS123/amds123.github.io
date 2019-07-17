---
layout: post
title: "Improved Reinforcement Learning through Imitation Learning Pretraining Towards Image-based Autonomous Driving"
date: 2019-07-16 04:48:52
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Tianqi Wang, Dong Eui Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a training pipeline for the autonomous driving task given the current camera image and vehicle speed as the input to produce the throttle, brake, and steering control output. The simulator Airsim's convenient weather and lighting API provides a sufficient diversity during training which can be very helpful to increase the trained policy's robustness. In order to not limit the possible policy's performance, we use a continuous and deterministic control policy setting. We utilize ResNet-34 as our actor and critic networks with some slight changes in the fully connected layers. Considering human's mastery of this task and the high-complexity nature of this task, we first use imitation learning to mimic the given human policy and leverage the trained policy and its weights to the reinforcement learning phase for which we use DDPG. This combination shows a considerable performance boost comparing to both pure imitation learning and pure DDPG for the autonomous driving task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06838](http://arxiv.org/abs/1907.06838)

##### PDF
[http://arxiv.org/pdf/1907.06838](http://arxiv.org/pdf/1907.06838)

