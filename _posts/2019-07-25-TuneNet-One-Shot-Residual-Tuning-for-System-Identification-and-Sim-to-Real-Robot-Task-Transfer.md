---
layout: post
title: "TuneNet: One-Shot Residual Tuning for System Identification and Sim-to-Real Robot Task Transfer"
date: 2019-07-25 17:01:43
categories: arXiv_RO
tags: arXiv_RO
author: Adam Allevato, Elaine Schaertl Short, Mitch Pryor, Andrea L. Thomaz
mathjax: true
---

* content
{:toc}

##### Abstract
As researchers teach robots to perform more and more complex tasks, the need for realistic simulation environments is growing. Existing techniques for closing the reality gap by approximating real-world physics often require extensive real world data and/or thousands of simulation samples. This paper presents TuneNet, a new machine learning-based method to directly tune the parameters of one model to match another using an $\textit{iterative residual tuning}$ technique. TuneNet estimates the parameter difference between two models using a single observation from the target and minimal simulation, allowing rapid, accurate and sample-efficient parameter estimation. The system can be trained via supervised learning over an auto-generated simulated dataset. We show that TuneNet can perform system identification, even when the true parameter values lie well outside the distribution seen during training, and demonstrate that simulators tuned with TuneNet outperform existing techniques for predicting rigid body motion. Finally, we show that our method can estimate real-world parameter values, allowing a robot to perform sim-to-real task transfer on a dynamic manipulation task unseen during training. We are also making a baseline implementation of our code available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11200](http://arxiv.org/abs/1907.11200)

##### PDF
[http://arxiv.org/pdf/1907.11200](http://arxiv.org/pdf/1907.11200)

