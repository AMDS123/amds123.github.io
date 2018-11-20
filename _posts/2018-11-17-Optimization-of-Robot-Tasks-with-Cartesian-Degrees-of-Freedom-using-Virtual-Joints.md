---
layout: post
title: "Optimization of Robot Tasks with Cartesian Degrees of Freedom using Virtual Joints"
date: 2018-11-17 10:29:30
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Martin Wei&#xdf;
mathjax: true
---

* content
{:toc}

##### Abstract
A common task in robotics is unloading identical goods from a tray with rectangular grid structure. This naturally leads to the idea of programming the process at one grid position only and translating the motion to the other grid points, saving teaching time. However this approach usually fails because of joint limits or singularities of the robot. If the task description has some redundancies, e.g. the objects are cylinders where one orientation angle is free for the gripping process, the motion may be modified to avoid workspace problems. We present a mathematical algorithm that allows the automatic generation of robot programs for pick-and-place applications with structured positions when the workpieces have some symmetry, resulting in a Cartesian degree of freedom for the process. The optimization uses the idea of a virtual joint which measures the distance of the desired TCP to the workspace such that the nonlinear optimization method is not bothered with unreachable positions. Combined with smoothed versions of the functions in the nonlinear program higher order algorithms can be used, with theoretical justification superior to many ad-hoc approaches used so far.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07137](http://arxiv.org/abs/1811.07137)

##### PDF
[http://arxiv.org/pdf/1811.07137](http://arxiv.org/pdf/1811.07137)

