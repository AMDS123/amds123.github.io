---
layout: post
title: "Learning-Based Proxy Collision Detection for Robot Motion Planning Applications"
date: 2019-02-21 17:56:06
categories: arXiv_RO
tags: arXiv_RO Object_Detection Detection
author: Nikhil Das, Michael Yip
mathjax: true
---

* content
{:toc}

##### Abstract
This paper demonstrates that collision detection-intensive applications such as robotic motion planning may be accelerated by performing collision checks with a machine learning model. We propose Fastron, a learning-based algorithm to model a robot's configuration space to be used as a proxy collision detector in place of standard geometric collision checkers. We demonstrate that leveraging the proxy collision detector results in up to an order of magnitude faster performance in robot simulation and planning than state-of-the-art collision detection libraries. Our results show that Fastron learns a model more than 100 times faster than a competing C-space modeling approach, while also providing theoretical guarantees of learning convergence. Using the OMPL motion planning libraries, we were able to generate initial motion plans across all experiments with varying robot and environment complexities. With Fastron, we can repeatedly perform planning from scratch at a 56 Hz rate, showing its application toward autonomous surgical assistance task in shared environments with human-controlled manipulators. All performance gains were achieved despite using only CPU-based calculations, suggesting further computational gains with a GPU approach that can parallelize tensor algebra. Code is available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08164](http://arxiv.org/abs/1902.08164)

##### PDF
[http://arxiv.org/pdf/1902.08164](http://arxiv.org/pdf/1902.08164)

