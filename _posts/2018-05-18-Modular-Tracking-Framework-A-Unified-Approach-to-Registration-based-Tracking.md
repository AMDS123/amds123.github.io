---
layout: post
title: "Modular Tracking Framework: A Unified Approach to Registration based Tracking"
date: 2018-05-18 02:15:42
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Abhineet Singh, Martin Jagersand
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a modular, extensible and highly efficient open source framework for registration based tracking called Modular Tracking Framework (MTF). Targeted at robotics applications, it is implemented entirely in C++ and designed from the ground up to easily integrate with systems that support any of several major vision and robotics libraries including OpenCV, ROS, ViSP and Eigen. It implements more methods, is faster, and more precise than other existing systems. Further, the theoretical basis for its design is a new way to conceptualize registration based trackers that decomposes them into three constituent sub modules - Search Method (SM), Appearance Model (AM) and State Space Model (SSM). 
 In the process, we integrate many important advances published after Baker \&amp; Matthews' landmark work in 2004. In addition to being a practical solution for fast and high precision tracking, MTF can also serve as a useful research tool by allowing existing and new methods for any of the sub modules to be studied better. When a new method is introduced for one of these, the breakdown can help to experimentally find the combination of methods for the others that is optimum for it. By extensive use of generic programming, MTF makes it easy to plug in a new method for any of the sub modules so that it can not only be tested comprehensively with existing methods but also become immediately available for deployment in any project that uses the framework. With 16 AMs, 11 SMs and 13 SSMs implemented already, MTF provides over 2000 distinct single layer trackers. It also allows two or more of these to be combined together in several ways to create a practically unlimited variety of novel multi layer trackers.

##### Abstract (translated by Google)
本文提出了一种模块化，可扩展且高效的开源框架，用于基于注册的跟踪，称为模块跟踪框架（MTF）。针对机器人应用程序，它完全使用C ++实现，并从头开始设计，可轻松与支持几种主要视觉和机器人库（包括OpenCV，ROS，ViSP和Eigen）的系统集成。它实现了更多的方法，比其他现有系统更快，更精确。此外，其设计的理论基础是将基于注册的跟踪器概念化的新方法，其将它们分解为三个组成子模块 - 搜索方法（SM），外观模型（AM）和状态空间模型（SSM）。
 在此过程中，我们整合了Baker＆amp; Matthews在2004年的里程碑式的工作。除了作为快速和高精度跟踪的实用解决方案之外，MTF还可以作为有用的研究工具，允许更好地研究任何子模块的现有和新方法。当针对其中一种方法引入新方法时，细分可以帮助实验性地找到最适合其他方法的方法组合。通过广泛使用泛型编程，MTF可以很容易地为任何子模块插入一种新方法，以便它不仅可以用现有方法进行全面测试，而且可以立即用于任何使用该框架的项目中进行部署。 MTF提供16个AM，11个SM和13个SSM，提供超过2000个不同的单层跟踪器。它还允许两种或更多种这些以多种方式组合在一起，以创建实际上无限多种新型多层追踪器。

##### URL
[http://arxiv.org/abs/1602.09130](http://arxiv.org/abs/1602.09130)

##### PDF
[http://arxiv.org/pdf/1602.09130](http://arxiv.org/pdf/1602.09130)

