---
layout: post
title: "Deconvolving convolution neural network for cell detection"
date: 2018-06-18 22:26:49
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Detection
author: Shan E Ahmed Raza, Khalid AbdulJabbar, Mariam Jamal-Hanjani, Selvaraju Veeriah, John Le Quesne, Charles Swanton, Yinyin Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic cell detection in histology images is a challenging task due to varying size, shape and features of cells and stain variations across a large cohort. Conventional deep learning methods regress the probability of each pixel belonging to the centre of a cell followed by detection of local maxima. We present deconvolution as an alternate approach to local maxima detection. The ground truth points are convolved with a mapping filter to generate artifical labels. A convolutional neural network (CNN) is modified to convolve it's output with the same mapping filter and is trained for the mapped labels. Output of the trained CNN is then deconvolved to generate points as cell detection. We compare our method with state-of-the-art deep learning approaches where the results show that the proposed approach detects cells with comparatively high precision and F1-score.

##### Abstract (translated by Google)
组织学图像中的自动细胞检测是一项具有挑战性的任务，因为细胞的大小，形状和特征以及整个大群体中的染色变异。常规深度学习方法回归每个像素属于细胞中心的概率，然后检测局部最大值。我们提出解卷积作为局部最大值检测的替代方法。地面真值点与映射过滤器进行卷积以生成人造标签。卷积神经网络（CNN）被修改以将其输出与相同的映射滤波器进行卷积，并对映射后的标签进行训练。训练后的CNN的输出然后被解卷积以生成点作为小区检测。我们将我们的方法与最先进的深度学习方法进行了比较，结果表明所提出的方法能够以相对较高的精度和F1分数检测细胞。

##### URL
[http://arxiv.org/abs/1806.06970](http://arxiv.org/abs/1806.06970)

##### PDF
[http://arxiv.org/pdf/1806.06970](http://arxiv.org/pdf/1806.06970)

