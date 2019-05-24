---
layout: post
title: "Deep Drone Racing: From Simulation to Reality with Domain Randomization"
date: 2019-05-21 03:57:22
categories: arXiv_RO
tags: arXiv_RO Drone CNN
author: Antonio Loquercio, Elia Kaufmann, Ren&#xe9; Ranftl, Alexey Dosovitskiy, Vladlen Koltun, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamically changing environments, unreliable state estimation, and operation under severe resource constraints are fundamental challenges for robotics, which still limit the deployment of small autonomous drones. We address these challenges in the context of autonomous, vision-based drone racing in dynamic environments. A racing drone must traverse a track with possibly moving gates at high speed. We enable this functionality by combining the performance of a state-of-the-art path-planning and control system with the perceptual awareness of a convolutional neural network (CNN). The CNN directly maps raw images to a desired waypoint and speed. Given the CNN output, the planner generates a short minimum-jerk trajectory segment that is tracked by a model-based controller to actuate the drone towards the waypoint. The resulting modular system has several desirable features: (i) it can run fully on-board, (ii) it does not require globally consistent state estimation, and (iii) it is both platform and domain independent. We extensively test the precision and robustness of our system, both in simulation and on a physical platform. In both domains, our method significantly outperforms the prior state of the art. In order to understand the limits of our approach, we additionally compare against professional human drone pilots with different skill levels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09727](http://arxiv.org/abs/1905.09727)

##### PDF
[http://arxiv.org/pdf/1905.09727](http://arxiv.org/pdf/1905.09727)

