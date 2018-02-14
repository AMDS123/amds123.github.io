---
layout: post
title: "REAS: Combining Numerical Optimization with SAT Solving"
date: 2018-02-13 00:29:31
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Jeevana Priya Inala, Sicun Gao, Soonho Kong, Armando Solar-Lezama
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present ReaS, a technique that combines numerical optimization with SAT solving to synthesize unknowns in a program that involves discrete and floating point computation. ReaS makes the program end-to-end differentiable by smoothing any Boolean expression that introduces discontinuity such as conditionals and relaxing the Boolean unknowns so that numerical optimization can be performed. On top of this, ReaS uses a SAT solver to help the numerical search overcome local solutions by incrementally fixing values to the Boolean expressions. We evaluated the approach on 5 case studies involving hybrid systems and show that ReaS can synthesize programs that could not be solved by previous SMT approaches.

##### Abstract (translated by Google)
在本文中，我们展示了ReaS，这是一种将数值优化与SAT解决方案相结合的技术，用于在涉及离散和浮点计算的程序中合成未知数。 ReaS通过平滑任何引入不连续性的布尔表达式（如条件和放宽布尔未知数以便可以执行数值优化）来使程序端对端可区分。最重要的是，ReaS使用SAT解算器来帮助数值搜索通过将值逐步固定到布尔表达式来克服局部解决方案。我们评估了涉及混合系统的5个案例研究的方法，并表明ReaS可以合成以前的SMT方法无法解决的程序。

##### URL
[http://arxiv.org/abs/1802.04408](http://arxiv.org/abs/1802.04408)

##### PDF
[http://arxiv.org/pdf/1802.04408](http://arxiv.org/pdf/1802.04408)

