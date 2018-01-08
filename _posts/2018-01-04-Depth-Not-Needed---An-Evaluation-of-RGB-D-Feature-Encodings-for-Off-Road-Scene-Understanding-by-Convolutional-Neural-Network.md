---
layout: post
title: "Depth Not Needed - An Evaluation of RGB-D Feature Encodings for Off-Road Scene Understanding by Convolutional Neural Network"
date: 2018-01-04 03:03:45
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Christopher J. Holder, Toby P. Breckon, Xiong Wei
mathjax: true
---

* content
{:toc}

##### Abstract
Scene understanding for autonomous vehicles is a challenging computer vision task, with recent advances in convolutional neural networks (CNNs) achieving results that notably surpass prior traditional feature driven approaches. However, limited work investigates the application of such methods either within the highly unstructured off-road environment or to RGBD input data. In this work, we take an existing CNN architecture designed to perform semantic segmentation of RGB images of urban road scenes, then adapt and retrain it to perform the same task with multichannel RGBD images obtained under a range of challenging off-road conditions. We compare two different stereo matching algorithms and five different methods of encoding depth information, including disparity, local normal orientation and HHA (horizontal disparity, height above ground plane, angle with gravity), to create a total of ten experimental variations of our dataset, each of which is used to train and test a CNN so that classification performance can be evaluated against a CNN trained using standard RGB input.

##### Abstract (translated by Google)
对于自主车辆的场景理解是具有挑战性的计算机视觉任务，卷积神经网络（CNN）的最新进展取得了显着超越先前的传统特征驱动方法的结果。然而，有限的工作调查了这种方法在高度无结构的越野环境或RGBD输入数据中的应用。在这项工作中，我们采用现有的CNN架构设计来对城市道路场景的RGB图像进行语义分割，然后对其进行适应和重新训练，以在具有挑战性的越野条件下获得多路RGBD图像来执行相同的任务。我们比较了两种不同的立体匹配算法和5种不同的编码深度信息的方法，包括视差，局部法线方向和HHA（水平视差，地平面以上的高度，重力的角度），总共创建10个实验变量，每一个都被用来训练和测试一个CNN，这样就可以根据使用标准RGB输入训练的CNN评估分类性能。

##### URL
[http://arxiv.org/abs/1801.01235](http://arxiv.org/abs/1801.01235)

##### PDF
[http://arxiv.org/pdf/1801.01235](http://arxiv.org/pdf/1801.01235)

