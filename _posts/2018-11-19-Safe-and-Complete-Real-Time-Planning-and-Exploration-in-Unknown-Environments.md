---
layout: post
title: "Safe and Complete Real-Time Planning and Exploration in Unknown Environments"
date: 2018-11-19 17:47:01
categories: arXiv_RO
tags: arXiv_RO
author: David Fridovich-Keil, Jaime F. Fisac, Claire J. Tomlin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new framework for motion planning that wraps around existing kinodynamic planners and guarantees recursive feasibility when operating in a priori unknown, static environments. Our approach makes strong guarantees about overall safety and collision avoidance by utilizing a robust controller derived from reachability analysis. We ensure that motion plans never exit the safe backward reachable set of the initial state, while safely exploring the space. This preserves the safety of the initial state, and guarantees that that we will eventually find the goal if it is possible to do so while exploring safely. We implement our framework in the Robot Operating System (ROS) software environment and demonstrate it in a real-time simulation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07834](http://arxiv.org/abs/1811.07834)

##### PDF
[http://arxiv.org/pdf/1811.07834](http://arxiv.org/pdf/1811.07834)

