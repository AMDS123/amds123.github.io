---
layout: post
title: "Learning Manipulation States and Actions for Efficient Non-prehensile Rearrangement Planning"
date: 2019-01-11 11:25:52
categories: arXiv_RO
tags: arXiv_RO Adversarial GAN Face Reinforcement_Learning
author: Joshua A. Haustein, Isac Arnekvist, Johannes Stork, Kaiyu Hang, Danica Kragic
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses non-prehensile rearrangement planning problems where a robot is tasked to rearrange objects among obstacles on a planar surface. We present an efficient planning algorithm that is designed to impose few assumptions on the robot's non-prehensile manipulation abilities and is simple to adapt to different robot embodiments. For this, we combine sampling-based motion planning with reinforcement learning and generative modeling. Our algorithm explores the composite configuration space of objects and robot as a search over robot actions, forward simulated in a physics model. This search is guided by a generative model that provides robot states from which an object can be transported towards a desired state, and a learned policy that provides corresponding robot actions. As an efficient generative model, we apply Generative Adversarial Networks. We implement and evaluate our approach for robots endowed with configuration spaces in SE(2). We demonstrate empirically the efficacy of our algorithm design choices and observe more than 2x speedup in planning time on various test scenarios compared to a state-of-the-art approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03557](http://arxiv.org/abs/1901.03557)

##### PDF
[http://arxiv.org/pdf/1901.03557](http://arxiv.org/pdf/1901.03557)

