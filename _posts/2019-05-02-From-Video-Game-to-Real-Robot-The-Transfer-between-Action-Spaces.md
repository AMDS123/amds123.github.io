---
layout: post
title: "From Video Game to Real Robot: The Transfer between Action Spaces"
date: 2019-05-02 13:42:51
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Janne Karttunen, Anssi Kanervisto, Ville Hautam&#xe4;ki, Ville Kyrki
mathjax: true
---

* content
{:toc}

##### Abstract
Training agents with reinforcement learning based techniques requires thousands of steps, which translates to long training periods when applied to robots. By training the policy in a simulated environment we avoid such limitation. Typically, the action spaces in a simulation and real robot are kept as similar as possible, but if we want to use a generic simulation environment, this strategy will not work. Video games, such as Doom (1993), offer a crude but multi-purpose environments that can used for learning various tasks. However, original Doom has four discrete actions for movement and the robot in our case has two continuous actions. In this work, we study the transfer between these two different action spaces. We begin with experiments in a simulated environment, after which we validate the results with experiments on a real robot. Results show that fine-tuning initially learned network parameters leads to unreliable results, but by keeping most of the neural network frozen we obtain above $90\%$ success rate in simulation and real robot experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00741](http://arxiv.org/abs/1905.00741)

##### PDF
[http://arxiv.org/pdf/1905.00741](http://arxiv.org/pdf/1905.00741)

