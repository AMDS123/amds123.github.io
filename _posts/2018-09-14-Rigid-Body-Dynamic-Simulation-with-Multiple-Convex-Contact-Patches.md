---
layout: post
title: "Rigid Body Dynamic Simulation with Multiple Convex Contact Patches"
date: 2018-09-14 18:17:45
categories: arXiv_RO
tags: arXiv_RO Face Detection
author: Jiayin Xie, Nilanjan Chakraborty
mathjax: true
---

* content
{:toc}

##### Abstract
We present a principled method for dynamic simulation of rigid bodies in intermittent contact with each other where the contact is assumed to be a non-convex contact patch that can be modeled as a union of convex patches. The prevalent assumption in simulating rigid bodies undergoing intermittent contact with each other is that the contact is a point contact. In recent work, we introduced an approach to simulate contacting rigid bodies with convex contact patches (line and surface contact). In this paper, for non-convex contact patches modeled as a union of convex patches, we formulate a discrete-time mixed complementarity problem where we solve the contact detection and integration of the equations of motion simultaneously. Thus, our method is a geometrically-implicit method and we prove that in our formulation, there is no artificial penetration between the contacting rigid bodies. We solve for the equivalent contact point (ECP) and contact impulse of each contact patch simultaneously along with the state, i.e., configuration and velocity of the objects. We provide empirical evidence to show that if the number of contact patches between two objects is less than or equal to three, the state evolution of the bodies is unique, although the contact impulses and ECP may not be unique. We also present simulation results showing that our method can seamlessly capture transition between different contact modes like non-convex patch to point (or line contact) and vice-versa during simulation.

##### Abstract (translated by Google)
我们提出了一种原理方法，用于动态模拟彼此间歇接触的刚体，其中假设接触是非凸接触面片，可以建模为凸面贴片的并集。模拟刚体经历间歇接触的普遍假设是接触是点接触。在最近的工作中，我们介绍了一种模拟接触刚体与凸接触面（线和面接触）的方法。在本文中，对于非凸接触片作为凸片的并集建模，我们制定了离散时间混合互补问题，其中我们同时解决了运动方程的接触检测和积分。因此，我们的方法是一种几何隐式方法，我们证明在我们的配方中，接触刚体之间没有人工渗透。我们同时求解每个接触面片的等效接触点（ECP）和接触脉冲以及状态，即物体的配置和速度。我们提供经验证据表明，如果两个物体之间的接触斑块的数量小于或等于三，则物体的状态演变是唯一的，尽管接触脉冲和ECP可能不是唯一的。我们还提供了仿真结果，表明我们的方法可以在仿真过程中无缝捕获不同接触模式之间的转换，如非凸补丁到点（或线接触），反之亦然。

##### URL
[http://arxiv.org/abs/1809.05555](http://arxiv.org/abs/1809.05555)

##### PDF
[http://arxiv.org/pdf/1809.05555](http://arxiv.org/pdf/1809.05555)

