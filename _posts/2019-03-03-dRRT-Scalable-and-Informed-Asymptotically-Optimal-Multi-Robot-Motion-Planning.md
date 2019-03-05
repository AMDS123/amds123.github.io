---
layout: post
title: "dRRT*: Scalable and Informed Asymptotically-Optimal Multi-Robot Motion Planning"
date: 2019-03-03 21:27:49
categories: arXiv_RO
tags: arXiv_RO
author: Rahul Shome, Kiril Solovey, Andrew Dobson, Dan Halperin, Kostas E. Bekris
mathjax: true
---

* content
{:toc}

##### Abstract
Many exciting robotic applications require multiple robots with many degrees of freedom, such as manipulators, to coordinate their motion in a shared workspace. Discovering high-quality paths in such scenarios can be achieved, in principle, by exploring the composite space of all robots. Sampling-based planners do so by building a roadmap or a tree data structure in the corresponding configuration space and can achieve asymptotic optimality. The hardness of motion planning, however, renders the explicit construction of such structures in the composite space of multiple robots impractical. This work proposes a scalable solution for such coupled multi-robot problems, which provides desirable path-quality guarantees and is also computationally efficient. In particular, the proposed \drrtstar\ is an informed, asymptotically-optimal extension of a prior sampling-based multi-robot motion planner, \drrt. The prior approach introduced the idea of building roadmaps for each robot and implicitly searching the tensor product of these structures in the composite space. This work identifies the conditions for convergence to optimal paths in multi-robot problems, which the prior method was not achieving. Building on this analysis, \drrt\ is first properly adapted so as to achieve the theoretical guarantees and then further extended so as to make use of effective heuristics when searching the composite space of all robots. The case where the various robots share some degrees of freedom is also studied. Evaluation in simulation indicates that the new algorithm, \drrtstar\, converges to high-quality paths quickly and scales to a higher number of robots where various alternatives fail. This work also demonstrates the planner's capability to solve problems involving multiple real-world robotic arms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00994](http://arxiv.org/abs/1903.00994)

##### PDF
[http://arxiv.org/pdf/1903.00994](http://arxiv.org/pdf/1903.00994)

