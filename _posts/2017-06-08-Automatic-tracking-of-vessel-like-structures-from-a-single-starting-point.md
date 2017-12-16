---
layout: post
title: "Automatic tracking of vessel-like structures from a single starting point"
date: 2017-06-08 02:45:27
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Dario Augusto Borges Oliveira, Laura Leal-Taixe, Raul Queiroz Feitosa, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
The identification of vascular networks is an important topic in the medical image analysis community. While most methods focus on single vessel tracking, the few solutions that exist for tracking complete vascular networks are usually computationally intensive and require a lot of user interaction. In this paper we present a method to track full vascular networks iteratively using a single starting point. Our approach is based on a cloud of sampling points distributed over concentric spherical layers. We also proposed a vessel model and a metric of how well a sample point fits this model. Then, we implement the network tracking as a min-cost flow problem, and propose a novel optimization scheme to iteratively track the vessel structure by inherently handling bifurcations and paths. The method was tested using both synthetic and real images. On the 9 different data-sets of synthetic blood vessels, we achieved maximum accuracies of more than 98\%. We further use the synthetic data-set to analyse the sensibility of our method to parameter setting, showing the robustness of the proposed algorithm. For real images, we used coronary, carotid and pulmonary data to segment vascular structures and present the visual results. Still for real images, we present numerical and visual results for networks of nerve fibers in the olfactory system. Further visual results also show the potential of our approach for identifying vascular networks topologies. The presented method delivers good results for the several different datasets tested and have potential for segmenting vessel-like structures. Also, the topology information, inherently extracted, can be used for further analysis to computed aided diagnosis and surgical planning. Finally, the method's modular aspect holds potential for problem-oriented adjustments and improvements.

##### Abstract (translated by Google)
血管网络的识别是医学图像分析界的一个重要课题。虽然大多数方法专注于单船跟踪，但为了跟踪完整的血管网络而存在的少数解决方案通常是计算密集型的并且需要大量的用户交互。在本文中，我们提出一种方法来跟踪全血管网络迭代使用一个单一的起点。我们的方法是基于分布在同心球形层上的一组采样点。我们还提出了一个船模型和一个样本点适合这个模型的度量。然后，我们将网络跟踪作为最小费用流问题来实现，并提出了一种新的优化方案，通过固有地处理分支和路径来迭代地跟踪船舶结构。该方法使用合成和真实图像进行测试。在9个不同的合成血管数据集上，我们达到了98％以上的最高精度。我们进一步使用综合数据集来分析我们的方法对参数设置的敏感性，显示了该算法的鲁棒性。对于真实的图像，我们使用冠状动脉，颈动脉和肺部数据来分割血管结构并呈现视觉结果。仍然为真实的图像，我们提出嗅觉系统神经纤维网络的数字和视觉效果。进一步的视觉效果也显示了我们识别血管网络拓扑的方法的潜力。所提出的方法为测试的几个不同的数据集提供了良好的结果，并且具有分割血管样结构的潜力。此外，固有提取的拓扑信息可以用于进一步分析以计算辅助诊断和手术计划。最后，该方法的模块化方面具有面向问题的调整和改进的潜力。

##### URL
[https://arxiv.org/abs/1706.02434](https://arxiv.org/abs/1706.02434)

##### PDF
[https://arxiv.org/pdf/1706.02434](https://arxiv.org/pdf/1706.02434)

