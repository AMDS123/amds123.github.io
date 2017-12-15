---
layout: post
title: "Accelerating Eulerian Fluid Simulation With Convolutional Networks"
date: 2017-06-22 17:28:58
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Jonathan Tompson, Kristofer Schlachter, Pablo Sprechmann, Ken Perlin
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient simulation of the Navier-Stokes equations for fluid flow is a long standing problem in applied mathematics, for which state-of-the-art methods require large compute resources. In this work, we propose a data-driven approach that leverages the approximation power of deep-learning with the precision of standard solvers to obtain fast and highly realistic simulations. Our method solves the incompressible Euler equations using the standard operator splitting method, in which a large sparse linear system with many free parameters must be solved. We use a Convolutional Network with a highly tailored architecture, trained using a novel unsupervised learning framework to solve the linear system. We present real-time 2D and 3D simulations that outperform recently proposed data-driven methods; the obtained results are realistic and show good generalization properties.

##### Abstract (translated by Google)
用于流体流动的Navier-Stokes方程的有效仿真是应用数学中长期存在的问题，对此，最先进的方法需要大的计算资源。在这项工作中，我们提出了一种数据驱动的方法，利用深度学习的逼近能力和标准解算器的精度来获得快速和高度真实的模拟。我们的方法使用标准算子分裂方法求解不可压缩欧拉方程，其中必须解决具有许多自由参数的大稀疏线性系统。我们使用具有高度定制架构的卷积网络，使用新颖的无监督学习框架来训练来解决线性系统。我们提出的实时二维和三维模拟，胜过最近提出的数据驱动方法;得到的结果是逼真的，表现出良好的泛化特性。

##### URL
[https://arxiv.org/abs/1607.03597](https://arxiv.org/abs/1607.03597)

##### PDF
[https://arxiv.org/pdf/1607.03597](https://arxiv.org/pdf/1607.03597)

