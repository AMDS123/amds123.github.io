---
layout: post
title: "Neural Body Fitting: Unifying Deep Learning and Model-Based Human Pose and Shape Estimation"
date: 2018-08-17 17:56:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation Deep_Learning Prediction
author: Mohamed Omran, Christoph Lassner, Gerard Pons-Moll, Peter V. Gehler, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Direct prediction of 3D body pose and shape remains a challenge even for highly parameterized deep learning models. Mapping from the 2D image space to the prediction space is difficult: perspective ambiguities make the loss function noisy and training data is scarce. In this paper, we propose a novel approach (Neural Body Fitting (NBF)). It integrates a statistical body model within a CNN, leveraging reliable bottom-up semantic body part segmentation and robust top-down body model constraints. NBF is fully differentiable and can be trained using 2D and 3D annotations. In detailed experiments, we analyze how the components of our model affect performance, especially the use of part segmentations as an explicit intermediate representation, and present a robust, efficiently trainable framework for 3D human pose estimation from 2D images with competitive results on standard benchmarks. Code will be made available at <a href="http://github.com/mohomran/neural_body_fitting">this http URL</a>

##### Abstract (translated by Google)
即使对于高度参数化的深度学习模型，直接预测3D身体姿势和形状仍然是一个挑战。从2D图像空间到预测空间的映射是困难的：透视模糊性使得损失函数噪声并且训练数据是稀缺的。在本文中，我们提出了一种新方法（神经体拟合（NBF））。它在CNN中集成了统计体模型，利用可靠的自下而上的语义体部分分割和强大的自上而下的身体模型约束。 NBF是完全可区分的，可以使用2D和3D注释进行训练。在详细的实验中，我们分析了模型的组件如何影响性能，特别是使用零件分割作为明确的中间表示，并提供了一个强大，有效的可训练框架，用于从2D图像中进行3D人体姿态估计，并在标准基准上获得有竞争力的结果。代码将在<a href="http://github.com/mohomran/neural_body_fitting">此http URL </a>上提供

##### URL
[http://arxiv.org/abs/1808.05942](http://arxiv.org/abs/1808.05942)

##### PDF
[http://arxiv.org/pdf/1808.05942](http://arxiv.org/pdf/1808.05942)

