---
layout: post
title: "A Linear-Time Variational Integrator for Multibody Systems"
date: 2018-02-05 16:36:59
categories: arXiv_RO
tags: arXiv_RO
author: Jeongseok Lee, C. Karen Liu, Frank C. Park, Siddhartha S. Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient variational integrator for multibody systems. Variational integrators reformulate the equations of motion for multibody systems as discrete Euler-Lagrange (DEL) equations, transforming forward integration into a root-finding problem for the DEL equations. Variational integrators have been shown to be more robust and accurate in preserving fundamental properties of systems, such as momentum and energy, than many frequently used numerical integrators. However, state-of-the-art algorithms suffer from $O(n^3)$ complexity, which is prohibitive for articulated multibody systems with a large number of degrees of freedom, $n$, in generalized coordinates. Our key contribution is to derive a recursive algorithm that evaluates DEL equations in $O(n)$, which scales up well for complex multibody systems such as humanoid robots. Inspired by recursive Newton-Euler algorithm, our key insight is to formulate DEL equation individually for each body rather than for the entire system. Furthermore, we introduce a new quasi-Newton method that exploits the impulse-based dynamics algorithm, which is also $O(n)$, to avoid the expensive Jacobian inversion in solving DEL equations. We demonstrate scalability and efficiency, as well as extensibility to holonomic constraints through several case studies.

##### Abstract (translated by Google)
我们提出了一个有效的多体系统的变分积分器。变分积分器将多体系统的运动方程作为离散的欧拉 - 拉格朗日（DEL）方程重新表达，将正向积分转化为DEL方程的根发现问题。与许多常用的数值积分器相比，变分积分器在保持系统的基本性质（如动量和能量）方面显示出更强大和更精确。然而，现有技术的算法遭受$ O（n ^ 3）$复杂性，这对于在广义坐标中具有大量自由度n $的铰接多体系统是禁止的。我们的主要贡献是推导一个递归算法，用于评估$ O（n）$中的DEL方程，这对于复杂的多体系统（如人形机器人）可以很好地扩展。受到递归牛顿 - 欧拉算法的启发，我们的关键洞察是为每个物体而不是整个系统分别制定DEL方程。此外，我们引入一个新的准牛顿方法，利用基于脉冲的动力学算法，也是$ O（n）$，以避免昂贵的雅可比反演求解DEL方程。我们通过几个案例研究来证明可扩展性和效率，以及对完整约束的可扩展性。

##### URL
[http://arxiv.org/abs/1609.02898](http://arxiv.org/abs/1609.02898)

##### PDF
[http://arxiv.org/pdf/1609.02898](http://arxiv.org/pdf/1609.02898)

