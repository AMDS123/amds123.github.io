---
layout: post
title: "The Control Toolbox - An Open-Source C++ Library for Robotics, Optimal and Model Predictive Control"
date: 2018-01-12 19:08:37
categories: arXiv_RO
tags: arXiv_RO Face Optimization
author: Markus Giftthaler, Michael Neunert, Markus St&#xe4;uble, Jonas Buchli
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the Control Toolbox (CT), an open-source C++ library for efficient modelling, control, estimation, trajectory optimization and model predictive control. The CT is applicable to a broad class of dynamic systems, but features additional modelling tools specially designed for robotics. This paper outlines its general concept, its major building blocks and highlights selected application examples. The CT was designed for intuitive modelling of systems governed by ordinary differential- or difference equations. It supports rapid prototyping of cost functions and constraints and provides common interfaces for different optimal control solvers. To date, we support Single Shooting, the iterative Linear-Quadratic Regulator, Gauss-Newton Multiple Shooting and classical Direct Multiple Shooting. We provide interfaces to different NLP and linear-quadratic solvers, such as IPOPT, SNOPT, HPIPM, or a custom Riccati solver. The CT was designed with performance for online control in mind and allows to solve large-scale optimal control problems highly efficiently. Some of the key features enabling fast run-time performance are full support for Automatic Differentiation, derivative code generation and thorough multi-threading. For robotics problems, the we offer an interface to a fully auto-differentiable rigid-body dynamics modelling engine. In combination with derivative code generation, this allows for an unprecedented performance in solving optimal control problems for complex articulated robotic systems.

##### Abstract (translated by Google)
我们介绍了Control Toolbox（CT），一个用于高效建模，控制，评估，轨迹优化和模型预测控制的开源C ++库。 CT适用于广泛的动态系统，但是还有专门为机器人设计的其他建模工具。本文概述了其总体概念，主要构建模块和亮点，并选择了应用实例。 CT被设计用于由普通微分或差分方程控制的系统的直观建模。它支持成本函数和约束的快速原型设计，并为不同的最优控制求解器提供通用接口。迄今为止，我们支持单拍，迭代线性二次调节器，高斯牛顿多重拍摄和经典的直接多次拍摄。我们为不同的NLP和线性二次求解器提供接口，如IPOPT，SNOPT，HPIPM或自定义Riccati求解器。 CT在设计时考虑到了在线控制的性能，可以高效地解决大规模的最优控制问题。一些实现快速运行性能的关键特性是完全支持自动微分，派生代码生成和彻底的多线程。对于机器人问题，我们提供了一个全自动可微的刚体动力学建模引擎的接口。结合派生代码生成，这为解决复杂关节型机器人系统的最优控制问题提供了前所未有的性能。

##### URL
[http://arxiv.org/abs/1801.04290](http://arxiv.org/abs/1801.04290)

##### PDF
[http://arxiv.org/pdf/1801.04290](http://arxiv.org/pdf/1801.04290)

