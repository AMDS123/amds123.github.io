---
layout: post
title: "Combining Optimal Control and Learning for Visual Navigation in Novel Environments"
date: 2019-03-06 18:11:32
categories: arXiv_AI
tags: arXiv_AI
author: Somil Bansal, Varun Tolani, Saurabh Gupta, Jitendra Malik, Claire Tomlin
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based control is a popular paradigm for robot navigation because it can leverage a known dynamics model to efficiently plan robust robot trajectories. However, it is challenging to use model-based methods in settings where the environment is a priori unknown and can only be observed partially through on-board sensors on the robot. In this work, we address this short-coming by coupling model-based control with learning-based perception. The learning-based perception module produces a series of waypoints that guide the robot to the goal via a collision-free path. These waypoints are used by a model-based planner to generate a smooth and dynamically feasible trajectory that is executed on the physical system using feedback control. Our experiments in simulated real-world cluttered environments and on an actual ground vehicle demonstrate that the proposed approach can reach goal locations more reliably and efficiently in novel, previously-unknown environments as compared to a purely end-to-end learning-based alternative. Our approach is successfully able to exhibit goal-driven behavior without relying on detailed explicit 3D maps of the environment, works well with low frame rates, and generalizes well from simulation to the real world. Videos describing our approach and experiments are available on the project website.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02531](http://arxiv.org/abs/1903.02531)

##### PDF
[http://arxiv.org/pdf/1903.02531](http://arxiv.org/pdf/1903.02531)

