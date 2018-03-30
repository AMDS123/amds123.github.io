---
layout: post
title: "A Unified Framework for Multi-View Multi-Class Object Pose Estimation"
date: 2018-03-21 19:41:33
categories: arXiv_CV
tags: arXiv_CV Regularization Pose_Estimation CNN Inference Classification
author: Chi Li, Jin Bai, Gregory D. Hager
mathjax: true
---

* content
{:toc}

##### Abstract
One core challenge in object pose estimation is to ensure accurate and robust performance for large numbers of diverse foreground objects amidst complex background clutter. In this work, we present a scalable framework for accurately inferring six Degree-of-Freedom (6-DoF) pose for a large number of object classes from single or multiple views. To learn discriminative pose features, we integrate three new capabilities into a deep Convolutional Neural Network (CNN): an inference scheme that combines both classification and pose regression based on a uniform tessellation of SE(3), fusion of a class prior into the training process via a tiled class map, and an additional regularization using deep supervision with an object mask. Further, an efficient multi-view framework is formulated to address single-view ambiguity. We show this consistently improves the performance of the single-view network. We evaluate our method on three large-scale benchmarks: YCB-Video, JHUScene-50 and ObjectNet-3D. Our approach achieves competitive or superior performance over the current state-of-the-art methods.

##### Abstract (translated by Google)
对象姿态估计的一个核心挑战是确保在复杂的背景杂波中为大量不同的前景对象提供精确和稳健的性能。在这项工作中，我们提出了一个可扩展的框架，可以为单个或多个视图中的大量对象类准确推断六个自由度（6-DoF）姿态。为了学习辨别性姿态特征，我们将三种新功能集成到深度卷积神经网络（CNN）中：一种推理方案，它基于SE（3）的统一曲面细分将分类和姿态回归相结合，将一类先验融合到训练中通过平铺的类地图进行处理，以及使用深度监视和对象蒙版的附加正则化。此外，制定了一个有效的多视图框架来解决单视图模糊。我们证明这一贯地改善了单视图网络的性能。我们在三个大型基准测试中评估我们的方法：YCB-Video，JHUScene-50和ObjectNet-3D。我们的方法比目前最先进的方法实现了竞争力或卓越的性能。

##### URL
[https://arxiv.org/abs/1803.08103](https://arxiv.org/abs/1803.08103)

##### PDF
[https://arxiv.org/pdf/1803.08103](https://arxiv.org/pdf/1803.08103)

