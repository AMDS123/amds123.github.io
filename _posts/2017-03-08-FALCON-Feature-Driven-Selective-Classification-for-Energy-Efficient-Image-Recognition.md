---
layout: post
title: "FALCON: Feature Driven Selective Classification for Energy-Efficient Image Recognition"
date: 2017-03-08 15:16:19
categories: arXiv_CV
tags: arXiv_CV Attention Classification Recognition
author: Priyadarshini Panda, Aayush Ankit, Parami Wijesinghe, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Machine-learning algorithms have shown outstanding image recognition or classification performance for computer vision applications. However, the compute and energy requirement for implementing such classifier models for large-scale problems is quite high. In this paper, we propose Feature Driven Selective Classification (FALCON) inspired by the biological visual attention mechanism in the brain to optimize the energy-efficiency of machine-learning classifiers. We use the consensus in the characteristic features (color/texture) across images in a dataset to decompose the original classification problem and construct a tree of classifiers (nodes) with a generic-to-specific transition in the classification hierarchy. The initial nodes of the tree separate the instances based on feature information and selectively enable the latter nodes to perform object specific classification. The proposed methodology allows selective activation of only those branches and nodes of the classification tree that are relevant to the input while keeping the remaining nodes idle. Additionally, we propose a programmable and scalable Neuromorphic Engine (NeuE) that utilizes arrays of specialized neural computational elements to execute the FALCON based classifier models for diverse datasets. The structure of FALCON facilitates the reuse of nodes while scaling up from small classification problems to larger ones thus allowing us to construct classifier implementations that are significantly more efficient. We evaluate our approach for a 12-object classification task on the Caltech101 dataset and 10-object task on CIFAR-10 dataset by constructing FALCON models on the NeuE platform in 45nm technology. Our results demonstrate significant improvement in energy-efficiency and training time for minimal loss in output quality.

##### Abstract (translated by Google)
机器学习算法已经为计算机视觉应用显示了出色的图像识别或分类性能。然而，实现这种大规模问题的分类器模型的计算和能量需求是相当高的。在本文中，我们提出了受大脑中生物视觉注意机制启发的特征驱动选择分类（FALCON），以优化机器学习分类器的能量效率。我们使用数据集中图像特征（颜色/纹理）的共识来分解原始分类问题，并在分类层次结构中构建具有通用到特定转换的分类器（节点）树。树的初始节点基于特征信息分离实例，并选择性地使后者节点执行特定于对象的分类。所提出的方法允许选择性地激活分类树中与输入相关的分支和节点，同时保持其余节点空闲。此外，我们提出了一种可编程和可扩展的神经形态引擎（NeuE），它利用专门的神经元计算元件阵列来执行基于FALCON的分类器模型，用于不同的数据集。 FALCON的结构有利于节点的重用，同时可以从小分类问题扩展到更大的问题，从而使我们能够构建更高效的分类器实现。我们通过在NeuE平台上用45nm技术构建FALCON模型来评估我们在Caltech101数据集上的12个对象分类任务和在CIFAR-10数据集上的10个对象任务的方法。我们的研究结果表明，能源效率和培训时间显着提高，产出质量损失最小。

##### URL
[https://arxiv.org/abs/1609.03396](https://arxiv.org/abs/1609.03396)

##### PDF
[https://arxiv.org/pdf/1609.03396](https://arxiv.org/pdf/1609.03396)

