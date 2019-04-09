---
layout: post
title: "A Hybrid Compositional Approach to Optimal Mission Planning for Multi-rotor UAVs using Metric Temporal Logic"
date: 2019-04-08 04:17:48
categories: arXiv_RO
tags: arXiv_RO
author: Usman A. Fiaz, John S. Baras
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates a hybrid compositional approach to optimal mission planning for multi-rotor Unmanned Aerial Vehicles (UAVs). We consider a time critical search and rescue scenario with two quadrotors in a constrained environment. Metric Temporal Logic (MTL) is used to formally describe the task specifications. In order to capture the various modes of UAV operation, we utilize a hybrid model for the system with linearized dynamics around different operating points. We divide the mission into several sub-tasks by exploiting the invariant nature of various task specifications i.e., the mutual independence of safety and timing constraints along the way, and the different modes (i,e., dynamics) of the robot. For each sub-task, we translate the MTL formulae into linear constraints, and solve the associated optimal control problem for desired path using a Mixed Integer Linear Program (MILP) solver. The complete path is constructed by the composition of individual optimal sub-paths. We show that the resulting trajectory satisfies the task specifications, and the proposed approach leads to significant reduction in computational complexity of the problem, making it possible to implement in real-time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03830](http://arxiv.org/abs/1904.03830)

##### PDF
[http://arxiv.org/pdf/1904.03830](http://arxiv.org/pdf/1904.03830)

