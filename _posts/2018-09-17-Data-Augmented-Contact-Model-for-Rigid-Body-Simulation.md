---
layout: post
title: "Data-Augmented Contact Model for Rigid Body Simulation"
date: 2018-09-17 01:15:14
categories: arXiv_RO
tags: arXiv_RO
author: Yifeng Jiang, Jiazheng Sun, C. Karen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Accurately modeling contact behaviors for real-world, near-rigid materials remains a grand challenge for existing rigid-body physics simulators. This paper introduces a data-augmented contact model that incorporates analytical solutions with observed data to predict the 3D contact impulse which could result in rigid bodies bouncing, sliding or spinning in all directions. Our method enhances the expressiveness of the standard Coulomb contact model by learning the contact behaviors from the observed data, while preserving the fundamental contact constraints whenever possible. For example, a classifier is trained to approximate the transitions between static and dynamic frictions, while non-penetration constraint during collision is enforced analytically. Our method computes the aggregated effect of contact for the entire rigid body, instead of predicting the contact force for each contact point individually, removing the exponential decline in accuracy as the number of contact points increases.

##### Abstract (translated by Google)
对现实的近刚性材料准确建模接触行为仍然是现有刚体物理模拟器的一大挑战。本文介绍了一种数据增强接触模型，该模型将分析解决方案与观测数据相结合，以预测3D接触脉冲，从而导致刚体在各个方向上反弹，滑动或旋转。我们的方法通过学习观察数据的接触行为来增强标准库仑接触模型的表现力，同时尽可能保留基本的接触约束。例如，训练分类器以近似静态和动态摩擦之间的过渡，同时在分析期间强制执行碰撞期间的非穿透约束。我们的方法计算整个刚体的接触聚合效应，而不是单独预测每个接触点的接触力，随着接触点数量的增加消除准确度的指数下降。

##### URL
[http://arxiv.org/abs/1803.04019](http://arxiv.org/abs/1803.04019)

##### PDF
[http://arxiv.org/pdf/1803.04019](http://arxiv.org/pdf/1803.04019)

