---
layout: post
title: "Following High-level Navigation Instructions on a Simulated Quadcopter with Imitation Learning"
date: 2018-05-31 18:42:26
categories: arXiv_AI
tags: arXiv_AI
author: Valts Blukis, Nataly Brukhim, Andrew Bennett, Ross A. Knepper, Yoav Artzi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a method for following high-level navigation instructions by mapping directly from images, instructions and pose estimates to continuous low-level velocity commands for real-time control. The Grounded Semantic Mapping Network (GSMN) is a fully-differentiable neural network architecture that builds an explicit semantic map in the world reference frame by incorporating a pinhole camera projection model within the network. The information stored in the map is learned from experience, while the local-to-world transformation is computed explicitly. We train the model using DAggerFM, a modified variant of DAgger that trades tabular convergence guarantees for improved training speed and memory use. We test GSMN in virtual environments on a realistic quadcopter simulator and show that incorporating an explicit mapping and grounding modules allows GSMN to outperform strong neural baselines and almost reach an expert policy performance. Finally, we analyze the learned map representations and show that using an explicit map leads to an interpretable instruction-following model.

##### Abstract (translated by Google)
我们介绍一种通过直接从图像，指令和姿态估计映射到连续的低级速度命令以实时控制的高级导航指令的方法。基于地面的语义映射网络（GSMN）是一种完全可微的神经网络架构，通过在网络中引入针孔摄像机投影模型，在世界参考框架中建立一个明确的语义映射。存储在地图中的信息是从经验中学习的，而本地到世界的转换是明确计算的。我们使用DAggerFM对DAggerFM进行训练，DAggerFM是DAgger的一个修改版本，可以交换表格收敛保证以提高训练速度和内存使用。我们在一个现实的四轴飞行模拟器的虚拟环境中测试GSMN，并显示，结合一个明确的映射和接地模块，GSMN可以超越强大的神经基线，几乎可以达到专家级的策略性能。最后，我们分析学习的地图表示，并显示使用显式地图导致可解释的指令跟踪模型。

##### URL
[http://arxiv.org/abs/1806.00047](http://arxiv.org/abs/1806.00047)

##### PDF
[http://arxiv.org/pdf/1806.00047](http://arxiv.org/pdf/1806.00047)

