---
layout: post
title: "Learning Probabilistic Multi-Modal Actor Models for Vision-Based Robotic Grasping"
date: 2019-04-15 20:23:52
categories: arXiv_RO
tags: arXiv_RO Optimization Inference
author: Mengyuan Yan, Adrian Li, Mrinal Kalakrishnan, Peter Pastor
mathjax: true
---

* content
{:toc}

##### Abstract
Many previous works approach vision-based robotic grasping by training a value network that evaluates grasp proposals. These approaches require an optimization process at run-time to infer the best action from the value network. As a result, the inference time grows exponentially as the dimension of action space increases. We propose an alternative method, by directly training a neural density model to approximate the conditional distribution of successful grasp poses from the input images. We construct a neural network that combines Gaussian mixture and normalizing flows, which is able to represent multi-modal, complex probability distributions. We demonstrate on both simulation and real robot that the proposed actor model achieves similar performance compared to the value network using the Cross-Entropy Method (CEM) for inference, on top-down grasping with a 4 dimensional action space. Our actor model reduces the inference time by 3 times compared to the state-of-the-art CEM method. We believe that actor models will play an important role when scaling up these approaches to higher dimensional action spaces.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07319](http://arxiv.org/abs/1904.07319)

##### PDF
[http://arxiv.org/pdf/1904.07319](http://arxiv.org/pdf/1904.07319)

