---
layout: post
title: "Multiple Object Detection, Tracking and Long-Term Dynamics Learning in Large 3D Maps"
date: 2018-01-28 21:36:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Nils Bore, Patric Jensfelt, John Folkesson
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a method for tracking and learning the dynamics of all objects in a large scale robot environment. A mobile robot patrols the environment and visits the different locations one by one. Movable objects are discovered by change detection, and tracked throughout the robot deployment. For tracking, we extend the Rao-Blackwellized particle filter of previous work with birth and death processes, enabling the method to handle an arbitrary number of objects. Target births and associations are sampled using Gibbs sampling. The parameters of the system are then learnt using the Expectation Maximization algorithm in an unsupervised fashion. The system therefore enables learning of the dynamics of one particular environment, and of its objects. The algorithm is evaluated on data collected autonomously by a mobile robot in an office environment during a real-world deployment. We show that the algorithm automatically identifies and tracks the moving objects within 3D maps and infers plausible dynamics models, significantly decreasing the modeling bias of our previous work. The proposed method represents an improvement over previous methods for environment dynamics learning as it allows for learning of fine grained processes.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.09292](https://arxiv.org/abs/1801.09292)

##### PDF
[https://arxiv.org/pdf/1801.09292](https://arxiv.org/pdf/1801.09292)

