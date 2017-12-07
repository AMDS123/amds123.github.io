---
layout: post
title: "Energy-Efficient Object Detection using Semantic Decomposition"
date: 2016-09-20 14:38:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Priyadarshini Panda, Swagath Venkataramani, Abhronil Sengupta, Anand Raghunathan, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Machine-learning algorithms offer immense possibilities in the development of several cognitive applications. In fact, large scale machine-learning classifiers now represent the state-of-the-art in a wide range of object detection/classification problems. However, the network complexities of large-scale classifiers present them as one of the most challenging and energy intensive workloads across the computing spectrum. In this paper, we present a new approach to optimize energy efficiency of object detection tasks using semantic decomposition to build a hierarchical classification framework. We observe that certain semantic information like color/texture are common across various images in real-world datasets for object detection applications. We exploit these common semantic features to distinguish the objects of interest from the remaining inputs (non-objects of interest) in a dataset at a lower computational effort. We propose a 2-stage hierarchical classification framework, with increasing levels of complexity, wherein the first stage is trained to recognize the broad representative semantic features relevant to the object of interest. The first stage rejects the input instances that do not have the representative features and passes only the relevant instances to the second stage. Our methodology thus allows us to reject certain information at lower complexity and utilize the full computational effort of a network only on a smaller fraction of inputs to perform detection. We use color and texture as distinctive traits to carry out several experiments for object detection. Our experiments on the Caltech101/CIFAR10 dataset show that the proposed method yields 1.93x/1.46x improvement in average energy, respectively, over the traditional single classifier model.

##### Abstract (translated by Google)
机器学习算法为几种认知应用的开发提供了巨大的可能性。实际上，大规模机器学习分类器现在代表了广泛的对象检测/分类问题的最新技术。但是，大规模分类器的网络复杂性使其成为整个计算频谱中最具挑战性和高能耗的工作负载之一。在本文中，我们提出了一种利用语义分解来优化目标检测任务的能量效率的新方法来构建分层分类框架。我们观察到，某些语义信息（如颜色/纹理）在用于物体检测应用的实际数据集的各种图像中是很常见的。我们利用这些常见的语义特征，以较低的计算量将感兴趣的对象与数据集中剩余的输入（非感兴趣的对象）区分开来。我们提出了一个两阶段的分层分类框架，随着复杂程度的提高，其中第一阶段被训练识别与感兴趣对象相关的广泛代表性语义特征。第一阶段拒绝不具有代表特征的输入实例，并仅将相关实例传递到第二阶段。因此，我们的方法允许我们以较低的复杂度拒绝某些信息，并且仅在一小部分输入上利用网络的全部计算工作来执行检测。我们使用颜色和纹理作为独特的特征来进行多个实验来进行物体检测。我们在Caltech101 / CIFAR10数据集上进行的实验表明，与传统的单分类器模型相比，该方法的平均能量提高了1.93倍/ 1.46倍。

##### URL
[https://arxiv.org/abs/1509.08970](https://arxiv.org/abs/1509.08970)

##### PDF
[https://arxiv.org/pdf/1509.08970](https://arxiv.org/pdf/1509.08970)

