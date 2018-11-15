---
layout: post
title: "Learning to Compensate Photovoltaic Power Fluctuations from Images of the Sky by Imitating an Optimal Policy"
date: 2018-11-13 09:39:53
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Robin Spiess, Felix Berkenkamp, Jan Poland, Andreas Krause
mathjax: true
---

* content
{:toc}

##### Abstract
The energy output of photovoltaic (PV) power plants depends on the environment and thus fluctuates over time. As a result, PV power can cause instability in the power grid, in particular when increasingly used. Limiting the rate of change of the power output is a common way to mitigate these fluctuations, often with the help of large batteries. A reactive controller that uses these batteries to compensate ramps works in practice, but causes stress on the battery due to a high energy throughput. In this paper, we present a deep learning approach that uses images of the sky to compensate power fluctuations predictively and reduces battery stress. In particular, we show that the optimal control policy can be computed using information that is only available in hindsight. Based on this, we use imitation learning to train a neural network that approximates this hindsight-optimal policy, but uses only currently available sky images and sensor data. We evaluate our method on a large dataset of measurements and images from a real power plant and show that the trained policy reduces stress on the battery.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05788](http://arxiv.org/abs/1811.05788)

##### PDF
[http://arxiv.org/pdf/1811.05788](http://arxiv.org/pdf/1811.05788)

