---
layout: post
title: "Data Efficient Reinforcement Learning for Legged Robots"
date: 2019-07-08 13:43:06
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Prediction
author: Yuxiang Yang, Ken Caluwaerts, Atil Iscen, Tingnan Zhang, Jie Tan, Vikas Sindhwani
mathjax: true
---

* content
{:toc}

##### Abstract
We present a model-based framework for robot locomotion that achieves walking based on only 4.5 minutes (45,000 control steps) of data collected on a quadruped robot. To accurately model the robot's dynamics over a long horizon, we introduce a loss function that tracks the model's prediction over multiple timesteps. We adapt model predictive control to account for planning latency, which allows the learned model to be used for real time control. Additionally, to ensure safe exploration during model learning, we embed prior knowledge of leg trajectories into the action space. The resulting system achieves fast and robust locomotion. Unlike model-free methods, which optimize for a particular task, our planner can use the same learned dynamics for various tasks, simply by changing the reward function. To the best of our knowledge, our approach is more than an order of magnitude more sample efficient than current model-free methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03613](http://arxiv.org/abs/1907.03613)

##### PDF
[http://arxiv.org/pdf/1907.03613](http://arxiv.org/pdf/1907.03613)

