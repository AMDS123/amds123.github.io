---
layout: post
title: "Semantic Segmentation via Highly Fused Convolutional Network with Multiple Soft Cost Functions"
date: 2018-01-04 11:55:55
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction
author: Tao Yang, Yan Wu, Junqiao Zhao, Linting Guan
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic image segmentation is one of the most challenged tasks in computer vision. In this paper, we propose a highly fused convolutional network, which consists of three parts: feature downsampling, combined feature upsampling and multiple predictions. We adopt a strategy of multiple steps of upsampling and combined feature maps in pooling layers with its corresponding unpooling layers. Then we bring out multiple pre-outputs, each pre-output is generated from an unpooling layer by one-step upsampling. Finally, we concatenate these pre-outputs to get the final output. As a result, our proposed network makes highly use of the feature information by fusing and reusing feature maps. In addition, when training our model, we add multiple soft cost functions on pre-outputs and final outputs. In this way, we can reduce the loss reduction when the loss is back propagated. We evaluate our model on three major segmentation datasets: CamVid, PASCAL VOC and ADE20K. We achieve a state-of-the-art performance on CamVid dataset, as well as considerable improvements on PASCAL VOC dataset and ADE20K dataset

##### Abstract (translated by Google)
语义图像分割是计算机视觉领域中最具挑战性的任务之一。在本文中，我们提出了一个高度融合的卷积网络，它由三部分组成：特征下采样，组合特征上采样和多重预测。我们采用了多步上采样的策略，并将特征映射与合并的图层合并为相应的解卷层。然后我们带出多个前置输出，每个前置输出是通过一步上取样从解耦层产生的。最后，我们连接这些前置输出以获得最终输出。因此，我们提出的网络通过融合和重用特征地图来高度利用特征信息。另外，在训练我们的模型时，我们在预输出和最终输出上增加了多个软成本函数。通过这种方式，我们可以减少损失在传播时的损失减少。我们在三个主要的细分数据集上评估我们的模型：CamVid，PASCAL VOC和ADE20K。我们在CamVid数据集上实现了最先进的性能，并在PASCAL VOC数据集和ADE20K数据集上进行了相当大的改进

##### URL
[http://arxiv.org/abs/1801.01317](http://arxiv.org/abs/1801.01317)

##### PDF
[http://arxiv.org/pdf/1801.01317](http://arxiv.org/pdf/1801.01317)

