---
layout: post
title: "An Efficient Decomposition Framework for Discriminative Segmentation with Supermodular Losses"
date: 2017-02-13 09:49:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Inference
author: Jiaqian Yu, Matthew B. Blaschko
mathjax: true
---

* content
{:toc}

##### Abstract
Several supermodular losses have been shown to improve the perceptual quality of image segmentation in a discriminative framework such as a structured output support vector machine (SVM). These loss functions do not necessarily have the same structure as the one used by the segmentation inference algorithm, and in general, we may have to resort to generic submodular minimization algorithms for loss augmented inference. Although these come with polynomial time guarantees, they are not practical to apply to image scale data. Many supermodular losses come with strong optimization guarantees, but are not readily incorporated in a loss augmented graph cuts procedure. This motivates our strategy of employing the alternating direction method of multipliers (ADMM) decomposition for loss augmented inference. In doing so, we create a new API for the structured SVM that separates the maximum a posteriori (MAP) inference of the model from the loss augmentation during training. In this way, we gain computational efficiency, making new choices of loss functions practical for the first time, while simultaneously making the inference algorithm employed during training closer to the test time procedure. We show improvement both in accuracy and computational performance on the Microsoft Research Grabcut database and a brain structure segmentation task, empirically validating the use of several supermodular loss functions during training, and the improved computational properties of the proposed ADMM approach over the Fujishige-Wolfe minimum norm point algorithm.

##### Abstract (translated by Google)
在结构化输出支持向量机（SVM）等区分性框架中，已经显示出几个超模损失来改善图像分割的感知质量。这些损失函数不一定具有分割推理算法所使用的结构，一般来说，我们可能不得不求助于通用的子模最小化算法来进行损失增强推理。虽然这些来自多项式时间保证，但它们不适用于图像尺度数据。许多超模损失具有强大的优化保证，但不容易纳入损失增强图切削程序。这激发了我们采用乘法器（ADMM）分解交替方向法进行损失增强推理的策略。为此，我们为结构化SVM创建了一个新的API，将训练过程中模型的最大后验（MAP）推断与损失增大分开。这样，我们获得了计算效率，使得损失函数的新选择首次实用化，同时使训练期间采用的推理算法更接近测试时间过程。我们在Microsoft Research Grabcut数据库和大脑结构分割任务上显示出精度和计算性能方面的改进，在训练过程中凭经验验证使用了几个超模块损失函数，以及改进的计算性能，相对于Fujishige-Wolfe最小值范数点算法。

##### URL
[https://arxiv.org/abs/1702.03690](https://arxiv.org/abs/1702.03690)

##### PDF
[https://arxiv.org/pdf/1702.03690](https://arxiv.org/pdf/1702.03690)

