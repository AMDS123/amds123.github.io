---
layout: post
title: "A Sequential Two-Step Algorithm for Fast Generation of Vehicle Racing Trajectories"
date: 2019-02-02 01:07:54
categories: arXiv_RO
tags: arXiv_RO Optimization Gradient_Descent
author: Nitin R. Kapania, John Subosits, J Christian Gerdes
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of maneuvering a vehicle through a race course in minimum time requires computation of both longitudinal (brake and throttle) and lateral (steering wheel) control inputs. Unfortunately, solving the resulting nonlinear optimal control problem is typically computationally expensive and infeasible for real-time trajectory planning. This paper presents an iterative algorithm that divides the path generation task into two sequential subproblems that are significantly easier to solve. Given an initial path through the race track, the algorithm runs a forward-backward integration scheme to determine the minimum-time longitudinal speed profile, subject to tire friction constraints. With this fixed speed profile, the algorithm updates the vehicle's path by solving a convex optimization problem that minimizes the resulting path curvature while staying within track boundaries and obeying affine, time-varying vehicle dynamics constraints. This two-step process is repeated iteratively until the predicted lap time no longer improves. While providing no guarantees of convergence or a globally optimal solution, the approach performs very well when validated on the Thunderhill Raceway course in Willows, CA. The predicted lap time converges after four to five iterations, with each iteration over the full 4.5 km race course requiring only thirty seconds of computation time on a laptop computer. The resulting trajectory is experimentally driven at the race circuit with an autonomous Audi TTS test vehicle, and the resulting lap time and racing line is comparable to both a nonlinear gradient descent solution and a trajectory recorded from a professional racecar driver. The experimental results indicate that the proposed method is a viable option for online trajectory planning in the near future.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00606](http://arxiv.org/abs/1902.00606)

##### PDF
[http://arxiv.org/pdf/1902.00606](http://arxiv.org/pdf/1902.00606)

