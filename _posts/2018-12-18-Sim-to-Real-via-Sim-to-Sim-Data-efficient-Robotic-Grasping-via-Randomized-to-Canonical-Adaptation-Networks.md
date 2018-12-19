---
layout: post
title: "Sim-to-Real via Sim-to-Sim: Data-efficient Robotic Grasping via Randomized-to-Canonical Adaptation Networks"
date: 2018-12-18 09:11:02
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Stephen James, Paul Wohlhart, Mrinal Kalakrishnan, Dmitry Kalashnikov, Alex Irpan, Julian Ibarz, Sergey Levine, Raia Hadsell, Konstantinos Bousmalis
mathjax: true
---

* content
{:toc}

##### Abstract
Real world data, especially in the domain of robotics, is notoriously costly to collect. One way to circumvent this can be to leverage the power of simulation in order to produce large amounts of labelled data. However, training models on simulated images does not readily transfer to real-world ones. Using domain adaptation methods to cross this "reality gap" requires at best a large amount of unlabelled real-world data, whilst domain randomization alone can waste modeling power, rendering certain reinforcement learning (RL) methods unable to learn the task of interest. In this paper, we present Randomized-to-Canonical Adaptation Networks (RCANs), a novel approach to crossing the visual reality gap that uses no real-world data. Our method learns to translate randomized rendered images into their equivalent non-randomized, canonical versions. This in turn allows for real images to also be translated into canonical sim images. We demonstrate the effectiveness of this sim-to-real approach by training a vision-based closed-loop grasping reinforcement learning agent in simulation, and then transferring it to the real world to attain 70% zero-shot grasp success on unseen objects, a result that almost doubles the success of learning the same task directly on domain randomization alone. Additionally, by joint finetuning in the real-world with only 5,000 real-world grasps, our method achieves 91%, outperforming a state-of-the-art system trained with 580,000 real-world grasps, resulting in a reduction of real-world data by more than 99%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07252](http://arxiv.org/abs/1812.07252)

##### PDF
[http://arxiv.org/pdf/1812.07252](http://arxiv.org/pdf/1812.07252)

