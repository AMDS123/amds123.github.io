---
layout: post
title: "Bethe Projections for Non-Local Inference"
date: 2016-11-28 18:44:53
categories: arXiv_CL
tags: arXiv_CL Regularization Inference Prediction Gradient_Descent Recognition
author: Luke Vilnis, David Belanger, Daniel Sheldon, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Many inference problems in structured prediction are naturally solved by augmenting a tractable dependency structure with complex, non-local auxiliary objectives. This includes the mean field family of variational inference algorithms, soft- or hard-constrained inference using Lagrangian relaxation or linear programming, collective graphical models, and forms of semi-supervised learning such as posterior regularization. We present a method to discriminatively learn broad families of inference objectives, capturing powerful non-local statistics of the latent variables, while maintaining tractable and provably fast inference using non-Euclidean projected gradient descent with a distance-generating function given by the Bethe entropy. We demonstrate the performance and flexibility of our method by (1) extracting structured citations from research papers by learning soft global constraints, (2) achieving state-of-the-art results on a widely-used handwriting recognition task using a novel learned non-convex inference procedure, and (3) providing a fast and highly scalable algorithm for the challenging problem of inference in a collective graphical model applied to bird migration.

##### Abstract (translated by Google)
结构化预测中的许多推理问题自然地通过用复杂的非局部辅助目标来增强易处理的依赖性结构来解决。这包括变分推理算法的平均场家族，使用拉格朗日松弛或线性规划的软约束或硬约束推理，集合图形模型以及诸如后验正则化的半监督学习的形式。我们提出了一种方法来区分性地学习推理目标的大家庭，捕捉潜在变量的强大的非局部统计，同时使用由Bethe熵给出的距离生成函数，使用非欧几里得投影梯度下降来保持易于处理和可证明的快速推理。我们通过以下方式来证明我们方法的性能和灵活性：（1）通过学习软全局约束，从研究论文中提取结构化引文;（2）在广泛使用的手写识别任务上获得最新的结果， （3）为应用于鸟类迁徙的集合图模型中的挑战性推理问题提供快速且高度可伸缩的算法。

##### URL
[https://arxiv.org/abs/1503.01397](https://arxiv.org/abs/1503.01397)

##### PDF
[https://arxiv.org/pdf/1503.01397](https://arxiv.org/pdf/1503.01397)

