---
layout: post
title: "Modular Tracking Framework: A Unified Approach to Registration based Tracking"
date: 2016-09-28 16:50:57
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Abhineet Singh, Martin Jagersand
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a modular, extensible and highly efficient open source framework for registration based tracking targeted at robotics applications. It is implemented entirely in C++ and is designed from the ground up to easily integrate with systems that support any of several major vision and robotics libraries including OpenCV, ROS, ViSP and Eigen. It is also faster and more precise than other existing systems. To establish the theoretical basis for its design, a new way to conceptualize registration based trackers is introduced that decomposes them into three constituent sub modules - Search Method, Appearance Model and State Space Model. In the process, the seminal work by Baker & Matthews is extended with several important advances since its publication. In addition to being a practical solution for fast and high precision tracking, this system can also serve as a useful research tool by allowing existing and new methods for any of the sub modules to be studied better. When a new method is introduced for one of these, the breakdown can help to experimentally find the combination of methods for the others that is optimum for it. By extensive use of generic programming, the system makes it easy to plug in a new method for any of the sub modules so that it can not only be tested comprehensively with existing methods but also become immediately available for deployment in any project that uses the framework.

##### Abstract (translated by Google)
本文提出了一个模块化，可扩展，高效的开源框架，用于基于注册的跟踪机器人应用。它完全采用C ++实现，并且从头开始设计，可轻松地与支持几种主要视觉和机器人库（包括OpenCV，ROS，ViSP和Eigen）的系统集成。它比其他现有的系统更快，更精确。为了建立其设计的理论基础，引入了基于配准的跟踪器概念化的新方法，将其分解为三个子模块 - 搜索法，外观模型和状态空间模型。在此过程中，贝克和马修斯的开创性工作自发表以来取得了若干重大进展。除了作为快速和高精度跟踪的实用解决方案之外，该系统还可以作为一个有用的研究工具，允许更好地研究任何子模块的现有的和新的方法。当其中一种方法引入新的方法时，细分可以帮助实验找到最适合其他方法的组合方法。通过大量使用泛型编程，系统可以很容易地在一个新的方法插入任何子模块，使其不仅可以全面地与现有的方法进行测试，但也立即变成可用于部署在使用框架的任何项目。

##### URL
[https://arxiv.org/abs/1602.09130](https://arxiv.org/abs/1602.09130)

##### PDF
[https://arxiv.org/pdf/1602.09130](https://arxiv.org/pdf/1602.09130)

