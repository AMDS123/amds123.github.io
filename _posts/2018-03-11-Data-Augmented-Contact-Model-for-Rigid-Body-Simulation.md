---
layout: post
title: "Data-Augmented Contact Model for Rigid Body Simulation"
date: 2018-03-11 19:20:15
categories: arXiv_RO
tags: arXiv_RO Face
author: Yifeng Jiang, C. Karen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Accurately modeling contact behaviors for real-world, near-rigid materials remains a grand challenge for existing rigid-body physics simulators. This paper introduces a data-augmented contact model that incorporates analytical solutions with observed data to predict the contact impulse between a particular pair of objects (e.g. a specific robot foot contacting a specific surface). The method enhances the expressiveness of the standard Coulomb contact model by learning the contact behaviors from the observed data, while preserving the fundamental contact constraints whenever possible. For example, a classifier is trained to approximate the transitions between static and dynamic frictions, while non-penetration constraint during collision is enforced analytically. Our method computes the aggregated effect of contact at the rigid-body level, removing the exponential dependency on the number of contact points in many exiting contact handling algorithms.

##### Abstract (translated by Google)
准确地建模真实世界的近刚性材料的接触行为仍然是现有刚体物理模拟器的巨大挑战。本文介绍了一种数据增强接触模型，该模型将解析解与观察数据结合起来，以预测特定对物体（例如特定机器人足部接触特定表面）之间的接触冲量。该方法通过从观察数据中学习接触行为，同时尽可能地保持基本接触约束，从而增强标准库仑接触模型的表现力。例如，分类器被训练成近似于静态摩擦和动态摩擦之间的转换，而分析中强制执行碰撞期间的非穿透约束。我们的方法计算刚体层面的接触聚合效应，消除许多现有接触处理算法中接触点数量的指数依赖关系。

##### URL
[https://arxiv.org/abs/1803.04019](https://arxiv.org/abs/1803.04019)

##### PDF
[https://arxiv.org/pdf/1803.04019](https://arxiv.org/pdf/1803.04019)

