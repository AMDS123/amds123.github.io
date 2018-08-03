---
layout: post
title: "Robust Tracking with Model Mismatch for Fast and Safe Planning: an SOS Optimization Approach"
date: 2018-08-02 03:08:49
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Sumeet Singh, Mo Chen, Sylvia L. Herbert, Claire J. Tomlin, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
In the pursuit of real-time motion planning, a commonly adopted practice is to compute a trajectory by running a planning algorithm on a simplified, low-dimensional dynamical model, and then employ a feedback tracking controller that tracks such a trajectory by accounting for the full, high-dimensional system dynamics. While this strategy of planning with model mismatch generally yields fast computation times, there are no guarantees of dynamic feasibility, which hampers application to safety-critical systems. Building upon recent work that addressed this problem through the lens of Hamilton-Jacobi (HJ) reachability, we devise an algorithmic framework whereby one computes, offline, for a pair of "planner" (i.e., low-dimensional) and "tracking" (i.e., high-dimensional) models, a feedback tracking controller and associated tracking bound. This bound is then used as a safety margin when generating motion plans via the low-dimensional model. Specifically, we harness the computational tool of sum-of-squares (SOS) programming to design a bilinear optimization algorithm for the computation of the feedback tracking controller and associated tracking bound. The algorithm is demonstrated via numerical experiments, with an emphasis on investigating the trade-off between the increased computational scalability afforded by SOS and its intrinsic conservativeness. Collectively, our results enable scaling the appealing strategy of planning with model mismatch to systems that are beyond the reach of HJ analysis, while maintaining safety guarantees.

##### Abstract (translated by Google)
在追求实时运动规划时，通常采用的做法是通过在简化的低维动力学模型上运行规划算法来计算轨迹，然后使用反馈跟踪控制器通过考虑到这种轨迹来跟踪这样的轨迹。完整的高维系统动力学。虽然这种使用模型不匹配进行规划的策略通常会产生快速的计算时间，但是不能保证动态可行性，这会妨碍应用于安全关键系统。基于最近通过Hamilton-Jacobi（HJ）可达性解决这个问题的工作，我们设计了一个算法框架，由此可以离线计算一对“规划器”（即低维）和“跟踪”（即，高维）模型，反馈跟踪控制器和相关的跟踪界限。然后，当通过低维模型生成运动计划时，将该界限用作安全余量。具体来说，我们利用平方和（SOS）编程的计算工具来设计双线性优化算法，用于计算反馈跟踪控制器和相关的跟踪界限。该算法通过数值实验进行了演示，重点研究了SOS提供的增加的计算可扩展性与其内在的保守性之间的权衡。总的来说，我们的结果可以扩展规划的吸引力策略，模型与HJ分析无法达到的系统不匹配，同时保持安全保障。

##### URL
[http://arxiv.org/abs/1808.00649](http://arxiv.org/abs/1808.00649)

##### PDF
[http://arxiv.org/pdf/1808.00649](http://arxiv.org/pdf/1808.00649)

