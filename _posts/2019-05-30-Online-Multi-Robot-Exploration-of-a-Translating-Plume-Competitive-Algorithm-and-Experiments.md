---
layout: post
title: "Online Multi-Robot Exploration of a Translating Plume: Competitive Algorithm and Experiments"
date: 2019-05-30 18:57:15
categories: arXiv_RO
tags: arXiv_RO
author: Yoonchang Sung, Deeksha Dixit, Pratap Tokekar
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of exploring a translating plume with a team of aerial robots. The shape and the size of the plume are unknown to the robots. The objective is to find a tour for each robot such that they collectively explore the plume. Specifically, the tours must be such that each point in the plume must be visible from the field-of-view of some robot along its tour. We propose a recursive depth-first search-based algorithm that yields a constant competitive ratio for the exploration problem. The competitive ratio is $\frac{2(S_r+S_p)(R+\lfloor\log{R}\rfloor)}{(S_r-S_p)(1+\lfloor\log{R}\rfloor)}$ where $R$ is the number of robots, and $S_r$ and $S_p$ are the robot speed and the plume speed, respectively. We also consider a more realistic scenario where the plume shape is not restricted to grid cells but an arbitrary shape. We show our algorithm has $\frac{2(S_r+S_p)(18R+\lfloor\log{R}\rfloor)}{(S_r-S_p)(1+\lfloor\log{R}\rfloor)}$ competitive ratio under the fat condition. We empirically verify our algorithm using simulations as well as a proof-of-concept experiment mapping a stationary region.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02769](http://arxiv.org/abs/1811.02769)

##### PDF
[http://arxiv.org/pdf/1811.02769](http://arxiv.org/pdf/1811.02769)

