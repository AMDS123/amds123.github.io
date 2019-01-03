---
layout: post
title: "Probabilistically Safe Corridors to Guide Sampling-Based Motion Planning"
date: 2019-01-01 05:59:19
categories: arXiv_RO
tags: arXiv_RO
author: Jinwook Huh, Omur Arslan, Daniel D. Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a new probabilistically safe local steering primitive for sampling-based motion planning in complex high-dimensional configuration spaces. Our local steering procedure is based on a new notion of a convex probabilistically safe corridor that is constructed around a configuration using tangent hyperplanes of confidence ellipsoids of Gaussian mixture models learned from prior collision history. Accordingly, we propose to expand a random motion planning graph towards a sample goal using its projection onto probabilistically safe corridors, which efficiently exploits the local geometry of configuration spaces for selecting proper steering direction and adapting steering stepsize. We observe that the proposed local steering procedure generates effective steering motion around difficult regions of configuration spaces, such as narrow passages, while minimizing collision likelihood. We evaluate the proposed steering method with randomized motion planners in a number of planning scenarios, both in simulation and on a physical 7DoF robot arm, demonstrating the effectiveness of our safety guided local planner over the standard straight-line planner.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.00101](http://arxiv.org/abs/1901.00101)

##### PDF
[http://arxiv.org/pdf/1901.00101](http://arxiv.org/pdf/1901.00101)

