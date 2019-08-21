---
layout: post
title: "On Analog Gradient Descent Learning over Multiple Access Fading Channels"
date: 2019-08-20 16:03:23
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent
author: Tomer Sery, Kobi Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
We consider a distributed learning problem over multiple access channel (MAC) using a large wireless network. The computation is made by the network edge and is based on received data from a large number of distributed nodes which transmit over a noisy fading MAC. The objective function is a sum of the nodes' local loss functions. This problem has attracted a growing interest in distributed sensing systems, and more recently in federated learning. We develop a novel Gradient-Based Multiple Access (GBMA) algorithm to solve the distributed learning problem over MAC. Specifically, the nodes transmit an analog function of the local gradient using common shaping waveforms and the network edge receives a superposition of the analog transmitted signals used for updating the estimate. GBMA does not require power control or beamforming to cancel the fading effect as in other algorithms, and operates directly with noisy distorted gradients. We analyze the performance of GBMA theoretically, and prove that it can approach the convergence rate of the centralized gradient descent (GD) algorithm in large networks. Specifically, we establish a finite-sample bound of the error for both convex and strongly convex loss functions with Lipschitz gradient. Furthermore, we provide energy scaling laws for approaching the centralized convergence rate as the number of nodes increases. Finally, experimental results support the theoretical findings, and demonstrate strong performance of GBMA using synthetic and real data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.07463](https://arxiv.org/abs/1908.07463)

##### PDF
[https://arxiv.org/pdf/1908.07463](https://arxiv.org/pdf/1908.07463)

