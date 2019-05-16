---
layout: post
title: "Online Center of Mass Estimation for a Humanoid Wheeled Inverted Pendulum Robot"
date: 2019-05-14 23:56:44
categories: arXiv_RO
tags: arXiv_RO Gradient_Descent
author: Munzir Zafar, Akash Patel, Bogdan Vlahov, Nathaniel Glaser, Sergio Aguillera, Seth Hutchinson
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel application of robust control and online learning for the balancing of a n Degree of Freedom (DoF), Wheeled Inverted Pendulum (WIP) humanoid robot. Our technique condenses the inaccuracies of a mass model into a Center of Mass (CoM) error, balances despite this error, and uses online learning to update the mass model for a better CoM estimate. Using a simulated model of our robot, we meta-learn a set of excitory joint poses that makes our gradient descent algorithm quickly converge to an accurate (CoM) estimate. This simulated pipeline executes in a fully online fashion, using active disturbance rejection to address the mass errors that result from a steadily evolving mass model. Experiments were performed on a 19 DoF WIP, in which we manually acquired the data for the learned set of poses and show that the mass model produced by a gradient descent produces a CoM estimate that improves overall control and efficiency. This work contributes to a greater corpus of whole body control on the Golem Krang humanoid robot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03076](http://arxiv.org/abs/1810.03076)

##### PDF
[http://arxiv.org/pdf/1810.03076](http://arxiv.org/pdf/1810.03076)

