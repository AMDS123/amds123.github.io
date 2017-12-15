---
layout: post
title: "PERCH: Perception via Search for Multi-Object Recognition and Localization"
date: 2016-03-16 20:49:52
categories: arXiv_CV
tags: arXiv_CV Optimization Recognition
author: Venkatraman Narayanan, Maxim Likhachev
mathjax: true
---

* content
{:toc}

##### Abstract
In many robotic domains such as flexible automated manufacturing or personal assistance, a fundamental perception task is that of identifying and localizing objects whose 3D models are known. Canonical approaches to this problem include discriminative methods that find correspondences between feature descriptors computed over the model and observed data. While these methods have been employed successfully, they can be unreliable when the feature descriptors fail to capture variations in observed data; a classic cause being occlusion. As a step towards deliberative reasoning, we present PERCH: PErception via SeaRCH, an algorithm that seeks to find the best explanation of the observed sensor data by hypothesizing possible scenes in a generative fashion. Our contributions are: i) formulating the multi-object recognition and localization task as an optimization problem over the space of hypothesized scenes, ii) exploiting structure in the optimization to cast it as a combinatorial search problem on what we call the Monotone Scene Generation Tree, and iii) leveraging parallelization and recent advances in multi-heuristic search in making combinatorial search tractable. We prove that our system can guaranteedly produce the best explanation of the scene under the chosen cost function, and validate our claims on real world RGB-D test data. Our experimental results show that we can identify and localize objects under heavy occlusion--cases where state-of-the-art methods struggle.

##### Abstract (translated by Google)
在许多机器人领域，如灵活的自动化制造或个人帮助，一个基本的感知任务是识别和定位3D模型已知的物体。对这个问题的规范方法包括判别方法，该方法找出在模型上计算的特征描述符与观测数据之间的对应关系。虽然这些方法已经被成功地使用，但是当特征描述符未能捕获观察数据的变化时，它们可能是不可靠的;一个经典的原因是阻塞。作为进行审议推理的一个步骤，我们通过SeaRCH展示了PERCH：PErception，这是一种通过假设可能的场景以生成方式寻找观察到的传感器数据的最佳解释的算法。我们的贡献是：i）将多物体识别和定位任务作为优化问题在虚拟场景的空间中进行制定; ii）利用优化中的结构将其作为一个组合搜索问题，称为单调场景生成树，以及iii）利用并行化和多启发式搜索中的近期进展使得组合搜索易于处理。我们证明，我们的系统可以保证在选择的成本函数下产生最好的场景解释，并验证我们对现实世界RGB-D测试数据的要求。我们的实验结果表明，我们可以识别和定位在重度遮挡情况下的物体 - 最先进的方法挣扎的情况。

##### URL
[https://arxiv.org/abs/1510.05613](https://arxiv.org/abs/1510.05613)

##### PDF
[https://arxiv.org/pdf/1510.05613](https://arxiv.org/pdf/1510.05613)

