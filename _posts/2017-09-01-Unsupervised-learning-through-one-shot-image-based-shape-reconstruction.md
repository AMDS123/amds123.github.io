---
layout: post
title: "Unsupervised learning through one-shot image-based shape reconstruction"
date: 2017-09-01 23:15:28
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge Recognition
author: Dinesh Jayaraman, Ruohan Gao, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Objects are three-dimensional entities, but visual observations are largely 2D. Inferring 3D properties from individual 2D views is thus a generically useful skill that is critical to object perception. We ask the question: can we learn useful image representations by explicitly training a system to infer 3D shape from 2D views? The few prior attempts at single view 3D reconstruction all target the reconstruction task as an end in itself, and largely build category-specific models to get better reconstructions. In contrast, we are interested in this task as a means to learn generic visual representations that embed knowledge of 3D shape properties from arbitrary object views. We train a single category-agnostic neural network from scratch to produce a complete image-based shape representation from one view of a generic object in a single forward pass. Through comparison against several baselines on widely used shape datasets, we show that our system learns to infer shape for generic objects including even those from categories that are not present in the training set. In order to perform this "mental rotation" task, our system is forced to learn intermediate image representations that embed object geometry, without requiring any manual supervision. We show that these learned representations outperform other unsupervised representations on various semantic tasks, such as object recognition and object retrieval.

##### Abstract (translated by Google)
对象是三维实体，但视觉观察主要是二维的。因此，从单个2D视图推断3D属性对于物体感知是至关重要的一般有用的技巧。我们提出这样的问题：我们能否通过明确地训练系统来从2D视图推断3D形状，从而学习有用的图像表示？之前的单视图三维重建的尝试都是把重建任务作为目标本身，大量地建立类别特定的模型以获得更好的重建。相反，我们对这个任务感兴趣，作为学习通用视觉表示的一种手段，它嵌入了从任意对象视图中获得三维形状属性的知识。我们从零开始训练一个单独的与类别无关的神经网络，以便在单个正向通道中从一个通用对象的视图中生成一个完整的基于图像的形状表示。通过与广泛使用的形状数据集上的几条基线进行比较，我们发现我们的系统学习推断通用对象的形状，甚至包括那些在训练集中不存在的类别。为了执行这个“心理旋转”任务，我们的系统被迫学习嵌入对象几何体的中间图像表示，而不需要任何手动监视。我们表明，这些学习表示胜过其他无监督表示对各种语义任务，如对象识别和对象检索。

##### URL
[https://arxiv.org/abs/1709.00505](https://arxiv.org/abs/1709.00505)

##### PDF
[https://arxiv.org/pdf/1709.00505](https://arxiv.org/pdf/1709.00505)

