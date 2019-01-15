---
layout: post
title: "Low Level Control of a Quadrotor with Deep Model-Based Reinforcement learning"
date: 2019-01-11 20:30:42
categories: arXiv_RO
tags: arXiv_RO Regularization Knowledge Reinforcement_Learning Prediction
author: Nathan O. Lambert, Daniel S. Drew, Joseph Yaconelli, Roberto Calandra, Sergey Levine, Kristofer S.J. Pister
mathjax: true
---

* content
{:toc}

##### Abstract
Generating low-level robot controllers often requires manual parameters tuning and significant system knowledge, which can result in long design times for highly specialized controllers. With the growth of automation, the need for such controllers might grow faster than the number of expert designers. To address the problem of rapidly generating low-level controllers without domain knowledge, we propose using model-based reinforcement learning (MBRL) trained on few minutes of automatically generated data. In this paper, we explore the capabilities of MBRL on a Crazyflie quadrotor with rapid dynamics where existing classical control schemes offer a baseline against the new method's performance. To our knowledge, this is the first use of MBRL for low-level controlled hover of a quadrotor using only on-board sensors, direct motor input signals, and no initial dynamics knowledge. Our forward dynamics model for prediction is a neural network tuned to predict the state variables at the next time step, with a regularization term on the variance of predictions. The model predictive controller then transmits best actions from a GPU-enabled base station to the quadrotor firmware via radio. In our experiments, the quadrotor achieved hovering capability of up to 6 seconds with 3 minutes of experimental training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03737](http://arxiv.org/abs/1901.03737)

##### PDF
[http://arxiv.org/pdf/1901.03737](http://arxiv.org/pdf/1901.03737)

