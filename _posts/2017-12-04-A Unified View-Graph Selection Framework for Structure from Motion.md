---
layout: post
title:  'A Unified View-Graph Selection Framework for Structure from Motion'
date:   2017-12-05 19:45:13
categories: arXiv_CV
tags: arXiv_CV
author: Rajvi Shah, Visesh Chari, P J Narayanan
---

* content
{:toc}

##### Abstract
View-graph is an essential input to large-scale structure from motion (SfM) pipelines. Accuracy and efficiency of large-scale SfM is crucially dependent on the input view-graph. Inconsistent or inaccurate edges can lead to inferior or wrong reconstruction. Most SfM methods remove `undesirable' images and pairs using several, fixed heuristic criteria, and propose tailor-made solutions to achieve specific reconstruction objectives such as efficiency, accuracy, or disambiguation. In contrast to these disparate solutions, we propose a single optimization framework that can be used to achieve these different reconstruction objectives with task-specific cost modeling. We also construct a very efficient network-flow based formulation for its approximate solution. The abstraction brought on by this selection mechanism separates the challenges specific to datasets and reconstruction objectives from the standard SfM pipeline and improves its generalization. This paper demonstrates the application of the proposed view-graph framework with standard SfM pipeline for two particular use-cases, (i) accurate and ghost-free reconstructions of highly ambiguous datasets using costs based on disambiguation priors, and (ii) accurate and efficient reconstruction of large-scale Internet datasets using costs based on commonly used priors.

##### Abstract (translated by Google)
视图是运动（SfM）管道的大规模结构的基本输入。大规模SfM的准确性和效率至关重要依赖于输入视图。边缘不一致或不准确可能会导致重建失败或错误。大多数SfM方法使用几个固定的启发式标准去除“不良”图像和对，并提出量身定制的解决方案来实现特定的重建目标，如效率，准确性或消歧。与这些不同的解决方案相反，我们提出了一个单一的优化框架，可以用来实现这些不同的重建目标与任务特定的成本模型。我们还为其近似解决方案构建了非常有效的基于网络流的配方。这种选择机制所带来的抽象将标准SfM管道中数据集和重建目标所特有的挑战分离出来，并改进其泛化。本文展示了对于两个特定用例，使用标准SfM流水线提出的视图框架的应用，（i）使用基于消歧前提的成本精确且无鬼地重建高度模糊的数据集，以及（ii）准确和高效重建大规模的互联网数据集，使用基于常用先验的成本。

##### URL
[http://arxiv.org/abs/1708.01125](http://arxiv.org/abs/1708.01125)

