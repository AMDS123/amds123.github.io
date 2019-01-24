---
layout: post
title: "A Constraint Programming Approach to Simultaneous Task Allocation and Motion Scheduling for Industrial Dual-Arm Manipulation Tasks"
date: 2019-01-23 14:37:29
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Jan Kristof Behrens, Ralph Lange, Masoumeh Mansouri
mathjax: true
---

* content
{:toc}

##### Abstract
Modern lightweight dual-arm robots bring the physical capabilities to quickly take over tasks at typical industrial workplaces designed for workers. In times of mass-customization, low setup times including the instructing/specifying of new tasks are crucial to stay competitive. We propose a constraint programming approach to simultaneous task allocation and motion scheduling for such industrial manipulation and assembly tasks. The proposed approach covers dual-arm and even multi-arm robots as well as connected machines. The key concept are Ordered Visiting Constraints, a descriptive and extensible model to specify such tasks with their spatiotemporal requirements and task-specific combinatorial or ordering constraints. Our solver integrates such task models and robot motion models into constraint optimization problems and solves them efficiently using various heuristics to produce makespan-optimized robot programs. The proposed task model is robot independent and thus can easily be deployed to other robotic platforms. Flexibility and portability of our proposed model is validated through several experiments on different simulated robot platforms. We benchmarked our search strategy against a general-purpose heuristic. For large manipulation tasks with 200 objects, our solver implemented using Google's Operations Research tools and ROS requires less than a minute to compute usable plans.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07914](http://arxiv.org/abs/1901.07914)

##### PDF
[http://arxiv.org/pdf/1901.07914](http://arxiv.org/pdf/1901.07914)

