---
layout: post
title: "Online Decentralized Receding Horizon Trajectory Optimization for Multi-Robot systems"
date: 2018-12-28 17:59:44
categories: arXiv_RO
tags: arXiv_RO Optimization Detection
author: Govind Aadithya R, Shravan Krishnan, Vijay Arvindh, Sivanathan K
mathjax: true
---

* content
{:toc}

##### Abstract
A novel decentralised trajectory generation algorithm for Multi Agent systems is presented. Multi-robot systems have the capacity to transform lives in a variety of fields. But, trajectory generation for multi-robot systems is still in its nascent stage and limited to heavily controlled environments. To overcome that, an online trajectory optimization algorithm that generates collision-free trajectories for robots, when given initial state and desired end pose, is proposed. It utilizes a simple method for obstacle detection, local shape based maps for obstacles and communication of robots' current states. Using the local maps, safe regions are formulated. Based upon the communicated data, trajectories are predicted for other robots and incorporated for collision-avoidance by resizing the regions of free space that the robot can be in without colliding. A trajectory is then optimized constraining the robot to remain within the safe region with the trajectories represented by piecewise polynomials parameterized by time. The algorithm is implemented using a receding horizon principle. The proposed algorithm is extensively tested in simulations on Gazebo using ROS with fourth order differentially flat aerial robots and non-holonomic second order wheeled robots in structured and unstructured environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11135](http://arxiv.org/abs/1812.11135)

##### PDF
[http://arxiv.org/pdf/1812.11135](http://arxiv.org/pdf/1812.11135)

