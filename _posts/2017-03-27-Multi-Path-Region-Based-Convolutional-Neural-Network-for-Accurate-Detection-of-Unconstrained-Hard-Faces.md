---
layout: post
title: "Multi-Path Region-Based Convolutional Neural Network for Accurate Detection of Unconstrained 'Hard Faces'"
date: 2017-03-27 15:31:00
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Detection Face_Detection
author: Yuguang Liu, Martin D. Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale variations still pose a challenge in unconstrained face detection. To the best of our knowledge, no current face detection algorithm can detect a face as large as 800 x 800 pixels while simultaneously detecting another one as small as 8 x 8 pixels within a single image with equally high accuracy. We propose a two-stage cascaded face detection framework, Multi-Path Region-based Convolutional Neural Network (MP-RCNN), that seamlessly combines a deep neural network with a classic learning strategy, to tackle this challenge. The first stage is a Multi-Path Region Proposal Network (MP-RPN) that proposes faces at three different scales. It simultaneously utilizes three parallel outputs of the convolutional feature maps to predict multi-scale candidate face regions. The "atrous" convolution trick (convolution with up-sampled filters) and a newly proposed sampling layer for "hard" examples are embedded in MP-RPN to further boost its performance. The second stage is a Boosted Forests classifier, which utilizes deep facial features pooled from inside the candidate face regions as well as deep contextual features pooled from a larger region surrounding the candidate face regions. This step is included to further remove hard negative samples. Experiments show that this approach achieves state-of-the-art face detection performance on the WIDER FACE dataset "hard" partition, outperforming the former best result by 9.6% for the Average Precision.

##### Abstract (translated by Google)
大规模的变化仍然是无约束的人脸检测中的一个挑战。就我们所知，目前的人脸检测算法不能检测到800×800像素的人脸，同时在同一个图像中同时检测到像8×8像素那样小的人脸，同样具有很高的精度。我们提出了一个两阶段级联人脸检测框架，基于多路径区域的卷积神经网络（MP-RCNN），将深度神经网络与经典学习策略无缝地结合起来，以应对这一挑战。第一阶段是一个多路径区域提议网络（MP-RPN），它提出了三种不同尺度的人脸。它同时利用卷积特征映射的三个并行输出来预测多尺度候选人脸区域。 MP-RPN中嵌入了“发情”卷积技巧（与上采样滤波器卷积）和新提出的“硬”采样采样层，以进一步提升其性能。第二阶段是Boosted Forests分类器，它利用从候选人脸区域内部汇集的深度脸部特征以及从候选人脸区域周围较大区域汇集的深度上下文特征。包括此步骤以进一步去除硬阴性样品。实验表明，这种方法在WIDER FACE数据集“硬”分区上实现了最先进的人脸检测性能，平均精度比前者的最佳结果高出9.6％。

##### URL
[https://arxiv.org/abs/1703.09145](https://arxiv.org/abs/1703.09145)

##### PDF
[https://arxiv.org/pdf/1703.09145](https://arxiv.org/pdf/1703.09145)

