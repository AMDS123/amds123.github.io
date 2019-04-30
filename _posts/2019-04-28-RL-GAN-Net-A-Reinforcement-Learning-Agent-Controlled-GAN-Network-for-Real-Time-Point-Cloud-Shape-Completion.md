---
layout: post
title: "RL-GAN-Net: A Reinforcement Learning Agent Controlled GAN Network for Real-Time Point Cloud Shape Completion"
date: 2019-04-28 11:08:04
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge GAN Reinforcement_Learning Optimization Classification
author: Muhammad Sarmad, Hyunjoo Jenny Lee, Young Min Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We present RL-GAN-Net, where a reinforcement learning (RL) agent provides fast and robust control of a generative adversarial network (GAN). Our framework is applied to point cloud shape completion that converts noisy, partial point cloud data into a high-fidelity completed shape by controlling the GAN. While a GAN is unstable and hard to train, we circumvent the problem by (1) training the GAN on the latent space representation whose dimension is reduced compared to the raw point cloud input and (2) using an RL agent to find the correct input to the GAN to generate the latent space representation of the shape that best fits the current input of incomplete point cloud. The suggested pipeline robustly completes point cloud with large missing regions. To the best of our knowledge, this is the first attempt to train an RL agent to control the GAN, which effectively learns the highly nonlinear mapping from the input noise of the GAN to the latent space of point cloud. The RL agent replaces the need for complex optimization and consequently makes our technique real time. Additionally, we demonstrate that our pipelines can be used to enhance the classification accuracy of point cloud with missing data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12304](http://arxiv.org/abs/1904.12304)

##### PDF
[http://arxiv.org/pdf/1904.12304](http://arxiv.org/pdf/1904.12304)

