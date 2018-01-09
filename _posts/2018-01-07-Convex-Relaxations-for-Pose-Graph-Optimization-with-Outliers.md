---
layout: post
title: "Convex Relaxations for Pose Graph Optimization with Outliers"
date: 2018-01-07 02:18:28
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Luca Carlone, Giuseppe C. Calafiore
mathjax: true
---

* content
{:toc}

##### Abstract
Pose Graph Optimization involves the estimation of a set of poses from pairwise measurements and provides a formalization for many problems arising in mobile robotics and geometric computer vision. In this paper, we consider the case in which a subset of the measurements fed to pose graph optimization is spurious. Our first contribution is to develop robust estimators that can cope with heavy-tailed measurement noise, hence increasing robustness to the presence of outliers. Since the resulting estimators require solving nonconvex optimization problems, we further develop convex relaxations that approximately solve those problems via semidefinite programming. We then provide conditions under which the proposed relaxations are exact. Contrarily to existing approaches, our convex relaxations do not rely on the availability of an initial guess for the unknown poses, hence they are more suitable for setups in which such guess is not available (e.g., multi-robot localization, recovery after localization failure). We tested the proposed techniques in extensive simulations, and we show that some of the proposed relaxations are indeed tight (i.e., they solve the original nonconvex problem 10 exactly) and ensure accurate estimation in the face of a large number of outliers.

##### Abstract (translated by Google)
姿态图优化包括从成对测量中估计一组姿态，并为移动机器人和几何计算机视觉中出现的许多问题提供形式化。在本文中，我们考虑一些情况，其中馈送到姿态图优化的测量的子集是假的。我们的第一个贡献是开发可以处理重尾测量噪声的鲁棒估计器，从而增加对异常值存在的鲁棒性。由于得到的估计量需要求解非凸优化问题，我们进一步开发凸松弛函数，通过半定规划来近似解决这些问题。然后，我们提供一些条件，使得所提出的放松是准确的。与现有方法相反，我们的凸松弛不依赖于对未知姿态的初始猜测的可用性，因此它们更适合于这种猜测不可用的设置（例如，多机器人定位，定位失败后的恢复） 。我们在广泛的仿真中测试了所提出的技术，并且我们证明了一些所提出的松弛确实是紧密的（即，它们准确地解决了原始的非凸面问题10）并且确保在大量异常值的情况下的准确估计。

##### URL
[http://arxiv.org/abs/1801.02112](http://arxiv.org/abs/1801.02112)

##### PDF
[http://arxiv.org/pdf/1801.02112](http://arxiv.org/pdf/1801.02112)

