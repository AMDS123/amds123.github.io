---
layout: post
title: "Quotient-Space Motion Planning"
date: 2018-07-25 08:02:43
categories: arXiv_RO
tags: arXiv_RO
author: Andreas Orthey (LAAS-GEPETTO), Adrien Escande (CNRS-AIST JRL), Eiichi Yoshida (CNRS-AIST JRL)
mathjax: true
---

* content
{:toc}

##### Abstract
A motion planning algorithm computes the motion of a robot by computing a path through its configuration space. To improve the runtime of motion planning algorithms, we propose to nest robots in each other, creating a nested quotient-space decomposition of the configuration space. Based on this decomposition we define a new roadmap-based motion planning algorithm called the Quotient-space roadMap Planner (QMP). The algorithm starts growing a graph on the lowest dimensional quotient space, switches to the next quotient space once a valid path has been found, and keeps updating the graphs on each quotient space simultaneously until a valid path in the configuration space has been found. We show that this algorithm is probabilistically complete and outperforms a set of state-of-the-art algorithms implemented in the open motion planning library (OMPL).

##### Abstract (translated by Google)
运动规划算法通过计算通过其配置空间的路径来计算机器人的运动。为了改善运动规划算法的运行时间，我们建议将机器人相互嵌套，创建配置空间的嵌套商空间分解。基于这种分解，我们定义了一种新的基于路线图的运动规划算法，称为Quotient-space roadMap Planner（QMP）。该算法开始在最低维商空间上生成图，一旦找到有效路径就切换到下一个商空间，并且同时不断更新每个商空间上的图，直到找到配置空间中的有效路径。我们证明该算法在概率上是完整的，并且优于开放运动规划库（OMPL）中实现的一组最先进的算法。

##### URL
[http://arxiv.org/abs/1807.09468](http://arxiv.org/abs/1807.09468)

##### PDF
[http://arxiv.org/pdf/1807.09468](http://arxiv.org/pdf/1807.09468)

