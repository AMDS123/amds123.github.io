---
layout: post
title: "Dynamics Based 3D Skeletal Hand Tracking"
date: 2017-05-22 10:01:39
categories: arXiv_CV
tags: arXiv_CV Face Tracking Object_Tracking
author: Stan Melax, Leonid Keselman, Sterling Orsten
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking the full skeletal pose of the hands and fingers is a challenging problem that has a plethora of applications for user interaction. Existing techniques either require wearable hardware, add restrictions to user pose, or require significant computation resources. This research explores a new approach to tracking hands, or any articulated model, by using an augmented rigid body simulation. This allows us to phrase 3D object tracking as a linear complementarity problem with a well-defined solution. Based on a depth sensor's samples, the system generates constraints that limit motion orthogonal to the rigid body model's surface. These constraints, along with prior motion, collision/contact constraints, and joint mechanics, are resolved with a projected Gauss-Seidel solver. Due to camera noise properties and attachment errors, the numerous surface constraints are impulse capped to avoid overpowering mechanical constraints. To improve tracking accuracy, multiple simulations are spawned at each frame and fed a variety of heuristics, constraints and poses. A 3D error metric selects the best-fit simulation, helping the system handle challenging hand motions. Such an approach enables real-time, robust, and accurate 3D skeletal tracking of a user's hand on a variety of depth cameras, while only utilizing a single x86 CPU core for processing.

##### Abstract (translated by Google)
跟踪手和手指的完整骨架姿态是具有挑战性的问题，其具有用于用户交互的大量应用。现有技术要么需要可穿戴硬件，要么对用户姿势施加限制，要么需要大量计算资源。本研究通过使用增强刚体仿真来探索一种新的跟踪手或任何铰接模型的方法。这使我们能够将3D对象跟踪用一个明确的解决方案作为线性互补问题。基于深度传感器的样本，系统生成限制与刚体模型表面正交的运动的约束。这些约束以及先前的运动，碰撞/接触约束以及联合力学，都是通过Gauss-Seidel解算器来解决的。由于摄像机的噪声特性和附件误差，众多的表面限制被冲击上限以避免机械限制。为了提高跟踪精度，在每一帧都会产生多个模拟，并提供各种启发式，约束和姿势。 3D错误度量选择最适合的模拟，帮助系统处理具有挑战性的手部动作。这种方法能够在各种深度摄像机上实时，稳健，准确地对用户手部进行3D骨架跟踪，同时仅使用一个x86 CPU内核进行处理。

##### URL
[https://arxiv.org/abs/1705.07640](https://arxiv.org/abs/1705.07640)

##### PDF
[https://arxiv.org/pdf/1705.07640](https://arxiv.org/pdf/1705.07640)

