---
layout: post
title: "Self-Supervised Damage-Avoiding Manipulation Strategy Optimization via Mental Simulation"
date: 2017-12-20 12:47:39
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Tobias Fromm
mathjax: true
---

* content
{:toc}

##### Abstract
Everyday robotics are challenged to deal with autonomous product handling in applications like logistics or retail, possibly causing damage on the items during manipulation. Traditionally, most approaches try to minimize physical interaction with goods. However, we propose to take into account any unintended motion of objects in the scene and to learn manipulation strategies in a self-supervised way which minimize the potential damage. The presented approach consists of a planning method that determines the optimal sequence to manipulate a number of objects in a scene with respect to possible damage by simulating interaction and hence anticipating scene dynamics. The planned manipulation sequences are taken as input to a machine learning process which generalizes to new, unseen scenes in the same application scenario. This learned manipulation strategy is continuously refined in a self-supervised optimization cycle dur- ing load-free times of the system. Such a simulation-in-the-loop setup is commonly known as mental simulation and allows for efficient, fully automatic generation of training data as opposed to classical supervised learning approaches. In parallel, the generated manipulation strategies can be deployed in near-real time in an anytime fashion. We evaluate our approach on one industrial scenario (autonomous container unloading) and one retail scenario (autonomous shelf replenishment).

##### Abstract (translated by Google)
日常的机器人技术面临的挑战是在物流或零售等应用中处理自主产品处理，可能会在操作过程中对物品造成损害。传统上，大多数方法都尽量减少与物品的物理交互。但是，我们建议考虑场景中物体的任何意外运动，并以自我监督的方式学习操纵策略，以尽可能减少潜在的损害。所提出的方法由计划方法组成，该方法通过模拟交互并因此预测场景动态来确定用于操纵场景中的多个对象的最佳序列关于可能的损害。计划的操作序列被作为机器学习过程的输入，该过程在相同的应用场景中推广到新的，不可见的场景。这个学习的操纵策略在系统的无负载时间的自我监督优化周期中不断完善。这种模拟在环设置通常被称为心理模拟，并且与经典的监督式学习方法相比，允许高效的，全自动地生成训练数据。同时，生成的操作策略可以随时以近乎实时的方式部署。我们在一个工业场景（自主集装箱卸货）和一个零售场景（自动货架补货）上评估我们的方法。

##### URL
[https://arxiv.org/abs/1712.07452](https://arxiv.org/abs/1712.07452)

##### PDF
[https://arxiv.org/pdf/1712.07452](https://arxiv.org/pdf/1712.07452)

