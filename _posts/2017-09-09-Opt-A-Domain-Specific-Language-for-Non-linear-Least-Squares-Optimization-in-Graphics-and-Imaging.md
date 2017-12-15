---
layout: post
title: "Opt: A Domain Specific Language for Non-linear Least Squares Optimization in Graphics and Imaging"
date: 2017-09-09 13:23:33
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Zachary DeVito, Michael Mara, Michael Zollhöfer, Gilbert Bernstein, Jonathan Ragan-Kelley, Christian Theobalt, Pat Hanrahan, Matthew Fisher, Matthias Nießner
mathjax: true
---

* content
{:toc}

##### Abstract
Many graphics and vision problems can be expressed as non-linear least squares optimizations of objective functions over visual data, such as images and meshes. The mathematical descriptions of these functions are extremely concise, but their implementation in real code is tedious, especially when optimized for real-time performance on modern GPUs in interactive applications. In this work, we propose a new language, Opt (available under this http URL), for writing these objective functions over image- or graph-structured unknowns concisely and at a high level. Our compiler automatically transforms these specifications into state-of-the-art GPU solvers based on Gauss-Newton or Levenberg-Marquardt methods. Opt can generate different variations of the solver, so users can easily explore tradeoffs in numerical precision, matrix-free methods, and solver approaches. In our results, we implement a variety of real-world graphics and vision applications. Their energy functions are expressible in tens of lines of code, and produce highly-optimized GPU solver implementations. These solver have performance competitive with the best published hand-tuned, application-specific GPU solvers, and orders of magnitude beyond a general-purpose auto-generated solver.

##### Abstract (translated by Google)
许多图形和视觉问题可以被表达为目标函数在诸如图像和网格等可视数据上的非线性最小二乘优化。这些函数的数学描述是非常简洁的，但是它们在真实代码中的实现是单调乏味的，特别是在交互式应用中的现代GPU上的实时性能优化时。在这项工作中，我们提出了一种新的语言Opt（在这个http URL下可用），用于将这些目标函数简洁而高层次地写在图像或图形结构的未知数上。我们的编译器自动将这些规格转换为基于高斯 - 牛顿或Levenberg-Marquardt方法的最先进的GPU求解器。 Opt可以生成求解器的不同变体，因此用户可以轻松探索数值精度，无矩阵方法和求解器方法的折衷。在我们的结果中，我们实现了各种现实世界的图形和视觉应用程序。它们的能量函数可用数十行代码表示，并可生成高度优化的GPU求解器实现。这些解算器的性能与最佳发布的手动调整的，特定于应用程序的GPU求解器相比具有竞争力，并且比通用自动生成的求解器要高出数量级。

##### URL
[https://arxiv.org/abs/1604.06525](https://arxiv.org/abs/1604.06525)

##### PDF
[https://arxiv.org/pdf/1604.06525](https://arxiv.org/pdf/1604.06525)

