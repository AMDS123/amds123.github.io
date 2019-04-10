---
layout: post
title: "Simultaneous drone localisation and wind turbine model fitting during autonomous surface inspection"
date: 2019-04-09 08:28:36
categories: arXiv_RO
tags: arXiv_RO Face Drone
author: Oliver Moolan-Feroze, Konstantinos Karachalios, Dimitrios N. Nikolaidis, Andrew Calway
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for simultaneous localisation and wind turbine model fitting for a drone performing an automated surface inspection. We use a skeletal parameterisation of the turbine that can be easily integrated into a non-linear least squares optimiser, combined with a pose graph representation of the drone's 3-D trajectory, allowing us to optimise both sets of parameters simultaneously. Given images from an onboard camera, we use a CNN to infer projections of the skeletal model, enabling correspondence constraints to be established through a cost function. This is then coupled with GPS/IMU measurements taken at key frames in the graph to allow successive optimisation as the drone navigates around the turbine. We present two variants of the cost function, one based on traditional 2D point correspondences and the other on direct image interpolation within the inferred projections. Results from experiments on simulated and real-world data show that simultaneous optimisation provides improvements to localisation over only optimising the pose and that combined use of both cost functions proves most effective.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04523](http://arxiv.org/abs/1904.04523)

##### PDF
[http://arxiv.org/pdf/1904.04523](http://arxiv.org/pdf/1904.04523)

