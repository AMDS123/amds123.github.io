---
layout: post
title: "LS-Net: Learning to Solve Nonlinear Least Squares for Monocular Stereo"
date: 2018-09-09 13:20:00
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Ronald Clark, Michael Bloesch, Jan Czarnowski, Stefan Leutenegger, Andrew J. Davison
mathjax: true
---

* content
{:toc}

##### Abstract
Sum-of-squares objective functions are very popular in computer vision algorithms. However, these objective functions are not always easy to optimize. The underlying assumptions made by solvers are often not satisfied and many problems are inherently ill-posed. In this paper, we propose LS-Net, a neural nonlinear least squares optimization algorithm which learns to effectively optimize these cost functions even in the presence of adversities. Unlike traditional approaches, the proposed solver requires no hand-crafted regularizers or priors as these are implicitly learned from the data. We apply our method to the problem of motion stereo ie. jointly estimating the motion and scene geometry from pairs of images of a monocular sequence. We show that our learned optimizer is able to efficiently and effectively solve this challenging optimization problem.

##### Abstract (translated by Google)
平方和目标函数在计算机视觉算法中非常流行。但是，这些目标函数并不总是易于优化。解算者所做出的基本假设往往得不到满足，许多问题本质上都是不适合的。在本文中，我们提出了LS-Net，一种神经非线性最小二乘优化算法，即使在逆境中也能学习有效地优化这些代价函数。与传统方法不同，所提出的求解器不需要手工制作的正则化器或先验，因为这些是从数据中隐含地学习的。我们将我们的方法应用于运动立体声问题即。从单眼序列的成对图像联合估计运动和场景几何。我们展示了我们学到的优化器能够有效地解决这一具有挑战性的优化问题。

##### URL
[http://arxiv.org/abs/1809.02966](http://arxiv.org/abs/1809.02966)

##### PDF
[http://arxiv.org/pdf/1809.02966](http://arxiv.org/pdf/1809.02966)

