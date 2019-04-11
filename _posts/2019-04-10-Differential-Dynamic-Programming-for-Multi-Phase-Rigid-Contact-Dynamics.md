---
layout: post
title: "Differential Dynamic Programming for Multi-Phase Rigid Contact Dynamics"
date: 2019-04-10 09:01:20
categories: arXiv_AI
tags: arXiv_AI
author: Rohan Budhiraja, Justin Carpentier, Carlos Mastalli, Nicolas Mansard
mathjax: true
---

* content
{:toc}

##### Abstract
A common strategy today to generate efficient locomotion movements is to split the problem into two consecutive steps: the first one generates the contact sequence together with the centroidal trajectory, while the second one computes the whole-body trajectory that follows the centroidal pattern. Yet the second step is generally handled by a simple program such as an inverse kinematics solver. In contrast, we propose to compute the whole-body trajectory by using a local optimal control solver, namely Differential Dynamic Programming (DDP). Our method produces more efficient motions, with lower forces and smaller impacts, by exploiting the Angular Momentum (AM). With this aim, we propose an original DDP formulation exploiting the Karush-Kuhn-Tucker constraint of the rigid contact model. We experimentally show the importance of this approach by executing large steps walking on the real HRP-2 robot, and by solving the problem of attitude control under the absence of external forces.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05072](http://arxiv.org/abs/1904.05072)

##### PDF
[http://arxiv.org/pdf/1904.05072](http://arxiv.org/pdf/1904.05072)

