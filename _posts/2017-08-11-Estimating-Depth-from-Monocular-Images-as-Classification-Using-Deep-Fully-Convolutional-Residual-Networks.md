---
layout: post
title: "Estimating Depth from Monocular Images as Classification Using Deep Fully Convolutional Residual Networks"
date: 2017-08-11 06:52:36
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Yuanzhouhan Cao, Zifeng Wu, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Depth estimation from single monocular images is a key component of scene understanding and has benefited largely from deep convolutional neural networks (CNN) recently. In this article, we take advantage of the recent deep residual networks and propose a simple yet effective approach to this problem. We formulate depth estimation as a pixel-wise classification task. Specifically, we first discretize the continuous depth values into multiple bins and label the bins according to their depth range. Then we train fully convolutional deep residual networks to predict the depth label of each pixel. Performing discrete depth label classification instead of continuous depth value regression allows us to predict a confidence in the form of probability distribution. We further apply fully-connected conditional random fields (CRF) as a post processing step to enforce local smoothness interactions, which improves the results. We evaluate our approach on both indoor and outdoor datasets and achieve state-of-the-art performance.

##### Abstract (translated by Google)
单目单眼图像的深度估计是场景理解的一个关键组成部分，最近受到深度卷积神经网络（CNN）的大量好处。在这篇文章中，我们利用最近的深度残差网络，并提出一个简单而有效的方法来解决这个问题。我们制定深度估计作为一个像素明智的分类任务。具体而言，我们首先将连续的深度值离散化为多个分箱，并根据其深度范围标注分箱。然后，我们训练完全卷积深度残差网络来预测每个像素的深度标签。执行离散深度标签分类而不是连续的深度值回归允许我们以概率分布的形式预测置信度。我们进一步应用完全连接的条件随机场（CRF）作为后处理步骤来强化局部平滑交互，从而改善结果。我们在室内和室外数据集上评估我们的方法，并实现最先进的性能。

##### URL
[https://arxiv.org/abs/1605.02305](https://arxiv.org/abs/1605.02305)

##### PDF
[https://arxiv.org/pdf/1605.02305](https://arxiv.org/pdf/1605.02305)

