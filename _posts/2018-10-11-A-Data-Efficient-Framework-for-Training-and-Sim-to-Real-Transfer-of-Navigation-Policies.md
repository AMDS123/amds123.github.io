---
layout: post
title: "A Data-Efficient Framework for Training and Sim-to-Real Transfer of Navigation Policies"
date: 2018-10-11 07:22:54
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Homanga Bharadhwaj, Zihan Wang, Yoshua Bengio, Liam Paull
mathjax: true
---

* content
{:toc}

##### Abstract
Learning effective visuomotor policies for robots purely from data is challenging, but also appealing since a learning-based system should not require manual tuning or calibration. In the case of a robot operating in a real environment the training process can be costly, time-consuming, and even dangerous since failures are common at the start of training. For this reason, it is desirable to be able to leverage \textit{simulation} and \textit{off-policy} data to the extent possible to train the robot. In this work, we introduce a robust framework that plans in simulation and transfers well to the real environment. Our model incorporates a gradient-descent based planning module, which, given the initial image and goal image, encodes the images to a lower dimensional latent state and plans a trajectory to reach the goal. The model, consisting of the encoder and planner modules, is trained through a meta-learning strategy in simulation first. We subsequently perform adversarial domain transfer on the encoder by using a bank of unlabelled but random images from the simulation and real environments to enable the encoder to map images from the real and simulated environments to a similarly distributed latent representation. By fine tuning the entire model (encoder + planner) with far fewer real world expert demonstrations, we show successful planning performances in different navigation tasks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04871](https://arxiv.org/abs/1810.04871)

##### PDF
[https://arxiv.org/pdf/1810.04871](https://arxiv.org/pdf/1810.04871)

