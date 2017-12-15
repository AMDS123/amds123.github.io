---
layout: post
title: "Chained Predictions Using Convolutional Neural Networks"
date: 2016-10-23 17:08:29
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Prediction
author: Georgia Gkioxari, Alexander Toshev, Navdeep Jaitly
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an adaptation of the sequence-to-sequence model for structured output prediction in vision tasks. In this model the output variables for a given input are predicted sequentially using neural networks. The prediction for each output variable depends not only on the input but also on the previously predicted output variables. The model is applied to spatial localization tasks and uses convolutional neural networks (CNNs) for processing input images and a multi-scale deconvolutional architecture for making spatial predictions at each time step. We explore the impact of weight sharing with a recurrent connection matrix between consecutive predictions, and compare it to a formulation where these weights are not tied. Untied weights are particularly suited for problems with a fixed sized structure, where different classes of output are predicted in different steps. We show that chained predictions achieve top performing results on human pose estimation from single images and videos.

##### Abstract (translated by Google)
在本文中，我们提出了视觉任务中结构化输出预测的序列 - 序列模型的改进。在这个模型中，给定输入的输出变量是使用神经网络顺序预测的。每个输出变量的预测不仅取决于输入，还取决于之前预测的输出变量。该模型应用于空间定位任务，并使用卷积神经网络（CNN）处理输入图像和多尺度去卷积体系结构，在每个时间步进行空间预测。我们探索连续预测之间的经常连接矩阵的权重共享的影响，并将其与这些权重不相关的公式进行比较。无限重量特别适用于固定大小结构的问题，在不同的步骤中预测不同类别的产出。我们表明，链接的预测实现从单个图像和视频的人体姿态估计的最佳性能结果。

##### URL
[https://arxiv.org/abs/1605.02346](https://arxiv.org/abs/1605.02346)

##### PDF
[https://arxiv.org/pdf/1605.02346](https://arxiv.org/pdf/1605.02346)

