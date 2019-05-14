---
layout: post
title: "Real-Time Kinodynamic Motion Planning for Omnidirectional Mobile Robot Soccer using Rapidly-Exploring Random Tree in Dynamic Environment with Moving Obstacles"
date: 2019-05-12 18:17:18
categories: arXiv_RO
tags: arXiv_RO Adversarial Tracking
author: Fahri Ali Rahman, Igi Ardiyanto, Adha Imam Cahyadi
mathjax: true
---

* content
{:toc}

##### Abstract
RoboCup Middle Size League (RoboCup MSL) provides a standardized testbed for research on mobile robot navigation, multi-robot cooperation, communication and integration via robot soccer competition in which the environment is highly dynamic and adversarial. One of important research topic in such area is kinodynamic motion planning that plan the trajectory of the robot while avoiding obstacles and obeying its dynamics. Kinodynamic motion planning for omnidirectional robot based on kinodynamic-RRT* method is presented in this work. Trajectory tracking control to execute the planned trajectory is also considered in this work. Robot motion planning in translational and rotational direction are decoupled. Then we implemented kinodynamic-RRT* with double integrator model to plan the translational trajectory. The rotational trajectory is generated using minimum-time trajectory generator satisfying velocity and acceleration constraints. The planned trajectory is then tracked using PI-Control. To address changing environment, we developed concurrent sofware module for motion planning and trajectory tracking. The resulting system were applied and tested using RoboCup simulation system based on Robot Operating System (ROS). The simulation results that the motion planning system are able to generate collision-free trajectory and the trajectory tracking system are able to follow the generated trajectory. It is also shown that in highly dynamic environment the online scheme are able to re-plan the trajectory.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04762](http://arxiv.org/abs/1905.04762)

##### PDF
[http://arxiv.org/pdf/1905.04762](http://arxiv.org/pdf/1905.04762)

