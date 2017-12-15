---
layout: post
title: "Supervised Transformer Network for Efficient Face Detection"
date: 2016-07-19 09:15:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Dong Chen, Gang Hua, Fang Wen, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Large pose variations remain to be a challenge that confronts real-word face detection. We propose a new cascaded Convolutional Neural Network, dubbed the name Supervised Transformer Network, to address this challenge. The first stage is a multi-task Region Proposal Network (RPN), which simultaneously predicts candidate face regions along with associated facial landmarks. The candidate regions are then warped by mapping the detected facial landmarks to their canonical positions to better normalize the face patterns. The second stage, which is a RCNN, then verifies if the warped candidate regions are valid faces or not. We conduct end-to-end learning of the cascaded network, including optimizing the canonical positions of the facial landmarks. This supervised learning of the transformations automatically selects the best scale to differentiate face/non-face patterns. By combining feature maps from both stages of the network, we achieve state-of-the-art detection accuracies on several public benchmarks. For real-time performance, we run the cascaded network only on regions of interests produced from a boosting cascade face detector. Our detector runs at 30 FPS on a single CPU core for a VGA-resolution image.

##### Abstract (translated by Google)
大姿态变化仍然是面临真正的人脸检测的挑战。我们提出了一个新的级联卷积神经网络，被称为监督变压器网络，以解决这个挑战。第一阶段是多任务区域提议网络（RPN），其同时预测候选人脸区域以及相关的面部标志。然后通过将检测到的面部标志映射到其规范位置来使候选区域变形，以更好地标准化面部图案。第二阶段是RCNN，然后验证翘曲的候选区域是否是有效的脸部。我们进行级联网络的端到端学习，包括优化面部标志的规范位置。这个监督学习的转换自动选择最佳的尺度来区分面部/非面部模式。通过结合网络两个阶段的特征图，我们在几个公共基准上实现了最先进的检测精度。对于实时性能，我们只在由增强型级联面部检测器产生的兴趣区域上运行级联网络。我们的检测器以30 FPS的速度在单个CPU内核上运行，以获得VGA分辨率的图像。

##### URL
[https://arxiv.org/abs/1607.05477](https://arxiv.org/abs/1607.05477)

##### PDF
[https://arxiv.org/pdf/1607.05477](https://arxiv.org/pdf/1607.05477)

