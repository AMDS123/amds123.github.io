---
layout: post
title: "A clever elimination strategy for efficient minimal solvers"
date: 2017-03-15 17:44:37
categories: arXiv_CV
tags: arXiv_CV
author: Zuzana Kukelova, Joe Kileel, Bernd Sturmfels, Tomas Pajdla
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new insight into the systematic generation of minimal solvers in computer vision, which leads to smaller and faster solvers. Many minimal problem formulations are coupled sets of linear and polynomial equations where image measurements enter the linear equations only. We show that it is useful to solve such systems by first eliminating all the unknowns that do not appear in the linear equations and then extending solutions to the rest of unknowns. This can be generalized to fully non-linear systems by linearization via lifting. We demonstrate that this approach leads to more efficient solvers in three problems of partially calibrated relative camera pose computation with unknown focal length and/or radial distortion. Our approach also generates new interesting constraints on the fundamental matrices of partially calibrated cameras, which were not known before.

##### Abstract (translated by Google)
我们对计算机视觉中最小求解器的系统生成提出了新的见解，这导致了更小和更快的求解器。许多最小问题公式是线性和多项式方程的耦合集合，其中图像测量仅进入线性方程。我们证明，通过首先消除所有未出现在线性方程中的未知数，然后将解扩展到未知数的其余部分来解决这样的系统是有用的。这可以通过提升的线性化推广到完全非线性系统。我们证明，这种方法导致更有效的解算器在部分校准相机相机姿态计算与未知的焦距和/或径向失真的三个问题。我们的方法也对部分校准的相机的基本矩阵产生了新的有趣的约束，这在以前是未知的。

##### URL
[https://arxiv.org/abs/1703.05289](https://arxiv.org/abs/1703.05289)

##### PDF
[https://arxiv.org/pdf/1703.05289](https://arxiv.org/pdf/1703.05289)

