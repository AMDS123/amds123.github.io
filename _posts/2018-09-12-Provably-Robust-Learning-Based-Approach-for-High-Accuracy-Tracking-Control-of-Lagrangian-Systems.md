---
layout: post
title: "Provably Robust Learning-Based Approach for High-Accuracy Tracking Control of Lagrangian Systems"
date: 2018-09-12 16:16:00
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Mohamed K. Helwa, Adam Heins, Angela P. Schoellig
mathjax: true
---

* content
{:toc}

##### Abstract
Lagrangian systems represent a wide range of robotic systems, including manipulators, wheeled and legged robots, and quadrotors. Inverse dynamics control and feedforward linearization techniques are typically used to convert the complex nonlinear dynamics of Lagrangian systems to a set of decoupled double integrators, and then a standard, outer-loop controller can be used to calculate the commanded acceleration for the linearized system. However, these methods typically depend on having a very accurate system model, which is often not available in practice. While this challenge has been addressed in the literature using different learning approaches, most of these approaches do not provide safety guarantees in terms of stability of the learning-based control system. In this paper, we provide a novel, learning-based control approach based on Gaussian processes (GPs) that ensures both stability of the closed-loop system and high-accuracy tracking. We use GPs to approximate the error between the commanded acceleration and the actual acceleration of the system, and then use the predicted mean and variance of the GP to calculate an upper bound on the uncertainty of the linearized model. This uncertainty bound is then used in a robust, outer-loop controller to ensure stability of the overall system. Moreover, we show that the tracking error converges to a ball with a radius that can be made arbitrarily small. Furthermore, we verify the effectiveness of our approach via simulations on a 2 degree-of-freedom (DOF) planar manipulator and experimentally on a 6 DOF industrial manipulator.

##### Abstract (translated by Google)
拉格朗日系统代表了广泛的机器人系统，包括机械手，轮式和腿式机器人以及四旋翼飞行器。逆动态控制和前馈线性化技术通常用于将拉格朗日系统的复杂非线性动力学转换为一组解耦双积分器，然后可以使用标准的外环控制器来计算线性化系统的指令加速度。然而，这些方法通常依赖于具有非常精确的系统模型，这在实践中通常是不可用的。虽然在使用不同学习方法的文献中已经解决了这一挑战，但是大多数这些方法在基于学习的控制系统的稳定性方面不提供安全保证。在本文中，我们提供了一种基于高斯过程（GP）的新颖的基于学习的控制方法，该方法确保闭环系统的稳定性和高精度跟踪。我们使用GP来估计指令加速度和系统实际加速度之间的误差，然后使用GP的预测均值和方差来计算线性化模型的不确定性的上限。然后将该不确定性界限用于鲁棒的外环控制器中，以确保整个系统的稳定性。此外，我们表明跟踪误差收敛于一个半径可以任意小的球。此外，我们通过2自由度（DOF）平面机械手的仿真和6 DOF工业机械手的实验验证了我们的方法的有效性。

##### URL
[http://arxiv.org/abs/1804.01031](http://arxiv.org/abs/1804.01031)

##### PDF
[http://arxiv.org/pdf/1804.01031](http://arxiv.org/pdf/1804.01031)

