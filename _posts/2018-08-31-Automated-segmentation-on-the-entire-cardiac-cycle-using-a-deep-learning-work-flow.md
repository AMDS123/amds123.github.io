---
layout: post
title: "Automated segmentation on the entire cardiac cycle using a deep learning work-flow"
date: 2018-08-31 17:07:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Nicol&#xf3; Savioli, Miguel Silva Vieira, Pablo Lamata, Giovanni Montana
mathjax: true
---

* content
{:toc}

##### Abstract
The segmentation of the left ventricle (LV) from CINE MRI images is essential to infer important clinical parameters. Typically, machine learning algorithms for automated LV segmentation use annotated contours from only two cardiac phases, diastole, and systole. In this work, we present an analysis work-flow for fully-automated LV segmentation that learns from images acquired through the cardiac cycle. The workflow consists of three components: first, for each image in the sequence, we perform an automated localization and subsequent cropping of the bounding box containing the cardiac silhouette. Second, we identify the LV contours using a Temporal Fully Convolutional Neural Network (T-FCNN), which extends Fully Convolutional Neural Networks (FCNN) through a recurrent mechanism enforcing temporal coherence across consecutive frames. Finally, we further defined the boundaries using either one of two components: fully-connected Conditional Random Fields (CRFs) with Gaussian edge potentials and Semantic Flow. Our initial experiments suggest that significant improvement in performance can potentially be achieved by using a recurrent neural network component that explicitly learns cardiac motion patterns whilst performing LV segmentation.

##### Abstract (translated by Google)
从CINE MRI图像分割左心室（LV）对于推断重要的临床参数是必不可少的。通常，用于自动LV分割的机器学习算法仅使用来自两个心脏阶段，心脏舒张期和心脏收缩期的注释轮廓。在这项工作中，我们提出了一个分析工作流程，用于全自动LV分割，从心脏周期中获取的图像中学习。该工作流程由三个部分组成：首先，对于序列中的每个图像，我们执行自动定位和随后裁剪包含心脏轮廓的边界框。其次，我们使用时间完全卷积神经网络（T-FCNN）识别LV轮廓，其通过在连续帧中实施时间相干性的循环机制来扩展完全卷积神经网络（FCNN）。最后，我们使用两个组件中的任何一个进一步定义边界：具有高斯边缘势和语义流的完全连接的条件随机场（CRF）。我们的初步实验表明，通过使用在执行LV分割的同时明确学习心脏运动模式的递归神经网络组件，可以实现性能的显着改善。

##### URL
[http://arxiv.org/abs/1809.01015](http://arxiv.org/abs/1809.01015)

##### PDF
[http://arxiv.org/pdf/1809.01015](http://arxiv.org/pdf/1809.01015)

