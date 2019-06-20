---
layout: post
title: "Formal Verification of Obstacle Avoidance and Navigation of Ground Robots"
date: 2019-06-18 18:03:11
categories: arXiv_RO
tags: arXiv_RO
author: Stefan Mitsch, Khalil Ghorbal, David Vogelbacher, Andr&#xe9; Platzer
mathjax: true
---

* content
{:toc}

##### Abstract
The safety of mobile robots in dynamic environments is predicated on making sure that they do not collide with obstacles. In support of such safety arguments, we analyze and formally verify a series of increasingly powerful safety properties of controllers for avoiding both stationary and moving obstacles: (i) static safety, which ensures that no collisions can happen with stationary obstacles, (ii) passive safety, which ensures that no collisions can happen with stationary or moving obstacles while the robot moves, (iii) the stronger passive friendly safety in which the robot further maintains sufficient maneuvering distance for obstacles to avoid collision as well, and (iv) passive orientation safety, which allows for imperfect sensor coverage of the robot, i. e., the robot is aware that not everything in its environment will be visible. We complement these provably correct safety properties with liveness properties: we prove that provably safe motion is flexible enough to let the robot still navigate waypoints and pass intersections. We use hybrid system models and theorem proving techniques that describe and formally verify the robot's discrete control decisions along with its continuous, physical motion. Moreover, we formally prove that safety can still be guaranteed despite sensor uncertainty and actuator perturbation, and when control choices for more aggressive maneuvers are introduced. Our verification results are generic in the sense that they are not limited to the particular choices of one specific control algorithm but identify conditions that make them simultaneously apply to a broad class of control algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1605.00604](http://arxiv.org/abs/1605.00604)

##### PDF
[http://arxiv.org/pdf/1605.00604](http://arxiv.org/pdf/1605.00604)

