---
layout: post
title: "Joint axis estimation for fast and slow movements using weighted gyroscope and acceleration constraints"
date: 2019-03-18 10:40:41
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Fredrik Olsson, Thomas Seel, Dustin Lehmann, Kjartan Halvorsen
mathjax: true
---

* content
{:toc}

##### Abstract
Sensor-to-segment calibration is a crucial step in inertial motion tracking. When two segments are connected by a hinge joint, for example in human knee and finger joints as well as in many robotic limbs, then the joint axis vector must be identified in the intrinsic sensor coordinate systems. There exist methods that identify these coordinates by solving an optimization problem that is based on kinematic joint constraints, which involve either the measured accelerations or the measured angular rates. In the current paper we demonstrate that using only one of these constraints leads to inaccurate estimates at either fast or slow motions. We propose a novel method based on a cost function that combines both constraints. The restrictive assumption of a homogeneous magnetic field is avoided by using only accelerometer and gyroscope readings. To combine the advantages of both sensor types, the residual weights are adjusted automatically based on the estimated signal variances and a nonlinear weighting of the acceleration norm difference. The method is evaluated using real data from nine different motions of an upper limb exoskeleton. Results show that, unlike previous approaches, the proposed method yields accurate joint axis estimation after only five seconds for all fast and slow motions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07353](http://arxiv.org/abs/1903.07353)

##### PDF
[http://arxiv.org/pdf/1903.07353](http://arxiv.org/pdf/1903.07353)

