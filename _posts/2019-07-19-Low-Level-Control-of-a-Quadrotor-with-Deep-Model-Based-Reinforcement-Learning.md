---
layout: post
title: "Low Level Control of a Quadrotor with Deep Model-Based Reinforcement Learning"
date: 2019-07-19 16:27:46
categories: arXiv_RO
tags: arXiv_RO Knowledge Reinforcement_Learning
author: Nathan O. Lambert, Daniel S. Drew, Joseph Yaconelli, Roberto Calandra, Sergey Levine, Kristofer S.J. Pister
mathjax: true
---

* content
{:toc}

##### Abstract
Designing effective low-level robot controllers often entail platform-specific implementations that require manual heuristic parameter tuning, significant system knowledge, or long design times. With the rising number of robotic and mechatronic systems deployed across areas ranging from industrial automation to intelligent toys, the need for a general approach to generating low-level controllers is increasing. To address the challenge of rapidly generating low-level controllers, we argue for using model-based reinforcement learning (MBRL) trained on relatively small amounts of automatically generated (i.e., without system simulation) data. In this paper, we explore the capabilities of MBRL on a Crazyflie centimeter-scale quadrotor with rapid dynamics to predict and control at &lt;50Hz. To our knowledge, this is the first use of MBRL for controlled hover of a quadrotor using only on-board sensors, direct motor input signals, and no initial dynamics knowledge. Our controller leverages rapid simulation of a neural network forward dynamics model on a GPU-enabled base station, which then transmits the best current action to the quadrotor firmware via radio. In our experiments, the quadrotor achieved hovering capability of up to 6 seconds with 3 minutes of experimental training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03737](http://arxiv.org/abs/1901.03737)

##### PDF
[http://arxiv.org/pdf/1901.03737](http://arxiv.org/pdf/1901.03737)

