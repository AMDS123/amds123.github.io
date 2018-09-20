---
layout: post
title: "Characterising Across-Stack Optimisations for Deep Convolutional Neural Networks"
date: 2018-09-19 13:52:49
categories: arXiv_CV
tags: arXiv_CV CNN Inference Deep_Learning Detection
author: Jack Turner, Jos&#xe9; Cano, Valentin Radu, Elliot J. Crowley, Michael O&#x27;Boyle, Amos Storkey
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) are extremely computationally demanding, presenting a large barrier to their deployment on resource-constrained devices. Since such systems are where some of their most useful applications lie (e.g. obstacle detection for mobile robots, vision-based medical assistive technology), significant bodies of work from both machine learning and systems communities have attempted to provide optimisations that will make CNNs available to edge devices. In this paper we unify the two viewpoints in a Deep Learning Inference Stack and take an across-stack approach by implementing and evaluating the most common neural network compression techniques (weight pruning, channel pruning, and quantisation) and optimising their parallel execution with a range of programming approaches (OpenMP, OpenCL) and hardware architectures (CPU, GPU). We provide comprehensive Pareto curves to instruct trade-offs under constraints of accuracy, execution time, and memory space.

##### Abstract (translated by Google)
卷积神经网络（CNN）的计算要求极高，对资源受限设备的部署提出了很大的障碍。由于这些系统是一些最有用的应用程序（例如移动机器人的障碍物检测，基于视觉的医疗辅助技术），机器学习和系统社区的大量工作都试图提供优化，使CNN可用于边缘设备。在本文中，我们统一了深度学习推理栈中的两个观点，并通过实现和评估最常见的神经网络压缩技术（权重修剪，通道修剪和量化）并使用范围优化其并行执行来采用跨堆栈方法编程方法（OpenMP，OpenCL）和硬件架构（CPU，GPU）。我们提供全面的Pareto曲线，以指导在准确性，执行时间和存储空间限制下的权衡。

##### URL
[http://arxiv.org/abs/1809.07196](http://arxiv.org/abs/1809.07196)

##### PDF
[http://arxiv.org/pdf/1809.07196](http://arxiv.org/pdf/1809.07196)

