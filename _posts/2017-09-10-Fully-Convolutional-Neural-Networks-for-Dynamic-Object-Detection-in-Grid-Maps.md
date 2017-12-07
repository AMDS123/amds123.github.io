---
layout: post
title: "Fully Convolutional Neural Networks for Dynamic Object Detection in Grid Maps"
date: 2017-09-10 17:06:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Florian Piewak, Timo Rehfeld, Michael Weber, J. Marius Zöllner
mathjax: true
---

* content
{:toc}

##### Abstract
Grid maps are widely used in robotics to represent obstacles in the environment and differentiating dynamic objects from static infrastructure is essential for many practical applications. In this work, we present a methods that uses a deep convolutional neural network (CNN) to infer whether grid cells are covering a moving object or not. Compared to tracking approaches, that use e.g. a particle filter to estimate grid cell velocities and then make a decision for individual grid cells based on this estimate, our approach uses the entire grid map as input image for a CNN that inspects a larger area around each cell and thus takes the structural appearance in the grid map into account to make a decision. Compared to our reference method, our concept yields a performance increase from 83.9% to 97.2%. A runtime optimized version of our approach yields similar improvements with an execution time of just 10 milliseconds.

##### Abstract (translated by Google)
网格地图在机器人技术中被广泛使用来表示环境中的障碍物，动态对象与静态基础设施的区分对于许多实际应用是必不可少的。在这项工作中，我们提出了一种使用深度卷积神经网络（CNN）来推断网格单元是否覆盖移动物体的方法。与跟踪方法相比，使用例如一个粒子滤波器来估计网格单元的速度，然后根据这个估计做出单个网格单元的决定，我们的方法使用整个网格地图作为CNN的输入图像，检查每个单元周围的较大区域，从而将结构外观把网格图考虑进去做出决定。与我们的参考方法相比，我们的概念性能从83.9％提高到97.2％。我们的方法的运行时优化版本产生类似的改进，执行时间仅为10毫秒。

##### URL
[https://arxiv.org/abs/1709.03139](https://arxiv.org/abs/1709.03139)

##### PDF
[https://arxiv.org/pdf/1709.03139](https://arxiv.org/pdf/1709.03139)

