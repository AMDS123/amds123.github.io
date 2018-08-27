---
layout: post
title: "SOTER: Programming Safe Robotics System using Runtime Assurance"
date: 2018-08-23 19:49:53
categories: arXiv_AI
tags: arXiv_AI Drone
author: Ankush Desai, Shromona Ghosh, Sanjit A. Seshia, Natarajan Shankar, Ashish Tiwari
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous robots increasingly depend on third-party off-the-shelf components and complex machine-learning techniques. This trend makes it challenging to provide strong design-time certification of correct operation. To address this challenge, we present SOTER, a programming framework that integrates the core principles of runtime assurance to enable the use of uncertified controllers, while still providing safety guarantees. 
 Runtime Assurance (RTA) is an approach used for safety-critical systems where design-time analysis is coupled with run-time techniques to switch between unverified advanced controllers and verified simple controllers. In this paper, we present a runtime assurance programming framework for modular design of provably-safe robotics software. \tool provides language primitives to declaratively construct a \rta module consisting of an advanced controller (untrusted), a safe controller (trusted), and the desired safety specification (S). If the RTA module is well formed then the framework provides a formal guarantee that it satisfies property S. The compiler generates code for monitoring system state and switching control between the advanced and safe controller in order to guarantee S. RTA allows complex systems to be constructed through the composition of RTA modules. 
 To demonstrate the efficacy of our framework, we consider a real-world case-study of building a safe drone surveillance system. Our experiments both in simulation and on actual drones show that RTA-enabled RTA ensures safety of the system, including when untrusted third-party components have bugs or deviate from the desired behavior.

##### Abstract (translated by Google)
自主机器人越来越依赖于第三方现成的组件和复杂的机器学习技术。这种趋势使得提供正确操作的强设计时认证变得具有挑战性。为了应对这一挑战，我们提出了SOTER，这是一个编程框架，它集成了运行时保证的核心原则，可以使用未经认证的控制器，同时仍然提供安全保障。
 运行时保证（RTA）是一种用于安全关键系统的方法，其中设计时分析与运行时技术相结合，可在未经验证的高级控制器和经过验证的简单控制器之间切换。在本文中，我们提出了一个运行保证编程框架，用于可证明安全的机器人软件的模块化设计。 \ tool提供语言原语，以声明方式构建一个由高级控制器（不可信），安全控制器（可信）和所需安全规范（S）组成的\ rta模块。如果RTA模块格式良好，那么框架提供了满足属性S的正式保证。编译器生成用于监视高级和安全控制器之间的系统状态和切换控制的代码，以保证S. RTA允许构建复杂系统通过RTA模块的组成。
 为了证明我们框架的功效，我们考虑建立安全无人机监控系统的实际案例研究。我们在模拟和实际无人机上的实验表明，支持RTA的RTA可确保系统的安全性，包括不受信任的第三方组件存在缺陷或偏离所需行为的情况。

##### URL
[http://arxiv.org/abs/1808.07921](http://arxiv.org/abs/1808.07921)

##### PDF
[http://arxiv.org/pdf/1808.07921](http://arxiv.org/pdf/1808.07921)

