---
layout: post
title: "Fast, Anytime Motion Planning for Prehensile Manipulation in Clutter"
date: 2018-06-19 21:06:36
categories: arXiv_RO
tags: arXiv_RO Sparse Knowledge Optimization
author: Andrew Kimmel, Rahul Shome, Zakary Littlefield, Kostas Bekris
mathjax: true
---

* content
{:toc}

##### Abstract
Many methods have been developed for planning the motion of robotic arms for picking and placing, ranging from local optimization to global search techniques, which are effective for sparsely placed objects. Dense clutter, however, still adversely affects the success rate, computation times, and quality of solutions in many real-world setups. The current work integrates tools from existing methodologies and proposes a framework that achieves high success ratio in clutter with anytime performance by returning solutions quickly and improving their quality over time, measured in terms of end effector's displacement. The idea is to first explore the lower dimensional end effector's task space efficiently by ignoring the arm, and build a discrete approximation of a navigation function, which guides the end effector towards the set of available grasps or object placements. This is performed online, without prior knowledge of the scene. Then, an informed sampling-based planner for the entire arm uses Jacobian-based steering to reach promising end effector poses given the task space guidance. While informed, the method is also comprehensive and allows the exploration of alternative paths over time if the task space guidance does not lead to a solution. This paper evaluates the proposed method against alternatives in picking or placing tasks among varying amounts of clutter for two types of end effectors, a 3-fingered hand and a vacuum gripper. The results suggest that the method reliably provides higher quality solution paths quicker, with a higher success rate relative to alternatives.

##### Abstract (translated by Google)
已经开发了许多用于规划机器人手臂拾取和放置运动的方法，从局部优化到全球搜索技术，这些技术对于稀疏放置的物体是有效的。然而，在许多现实世界的设置中，密集杂波仍然会对成功率，计算时间和解决方案的质量产生不利影响。目前的工作集成了现有方法学的工具，并提出了一个框架，通过快速返回解决方案并随时间推移提高质量，以末端执行器的位移来衡量，从而在随时随地获得高成功率。这个想法是首先通过忽略手臂来有效地探索低维端部效应器的任务空间，并且建立导航功能的离散近似，该导航功能将末端执行器引向可用抓握或对象放置集合。这是在线执行的，无需事先了解场景。然后，根据任务空间指导，整个手臂采用基于抽样的策划者使用基于雅可比行列式转向来达到有前途的末端执行器姿态。在得到通知的同时，该方法也是全面的，并且如果任务空间指导未导致解决方案，则允许探索随着时间推移的替代路径。本文评估了针对两种类型的末端执行器，三指手和真空夹具在拾取或将任务置于不同数量的杂波中的替代方案的提议方法。结果表明，该方法可以更快地提供更高质量的解决方案路径，相对于替代方案具有更高的成功率。

##### URL
[http://arxiv.org/abs/1806.07465](http://arxiv.org/abs/1806.07465)

##### PDF
[http://arxiv.org/pdf/1806.07465](http://arxiv.org/pdf/1806.07465)

