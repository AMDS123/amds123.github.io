---
layout: post
title: "Multi-Scale Convolutional-Stack Aggregation for Robust White Matter Hyperintensities Segmentation"
date: 2018-07-13 15:56:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN
author: Hongwei Li, Jianguo Zhang, Mark Muehlau, Jan Kirschke, Bjoern Menze
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of both large and small white matter hyperintensities/lesions in brain MR images is a challenging task which has drawn much attention in recent years. We propose a multi-scale aggregation model framework to deal with volume-varied lesions. Firstly, we present a specifically-designed network for small lesion segmentation called Stack-Net, in which multiple convolutional layers are 'one-by-one' connected, aiming to preserve rich local spatial information of small lesions before the sub-sampling layer. Secondly, we aggregate multi-scale Stack-Nets with different receptive fields to learn multi-scale contextual information of both large and small lesions. Our model is evaluated on recent MICCAI WMH Challenge Dataset and outperforms the state-of-the-art on lesion recall and lesion F1-score under 5-fold cross validation. In addition, we further test our pre-trained models on a Multiple Sclerosis lesion dataset with 30 subjects under cross-center evaluation. Results show that the aggregation model is effective in learning multi-scale spatial information.

##### Abstract (translated by Google)
脑MR图像中大小白质高信号/病变的分割是一项具有挑战性的任务，近年来引起了很多关注。我们提出了一个多尺度聚合模型框架来处理体积变化的病变。首先，我们提出了一个专门设计的小病变分割网络，称为Stack-Net，其中多个卷积层是“一个一个”连接的，旨在保留子样本层之前的小病变的丰富的局部空间信息。其次，我们聚合具有不同感受野的多尺度Stack-Nets，以学习大小病变的多尺度上下文信息。我们的模型在最近的MICCAI WMH Challenge Dataset上进行了评估，并且在5倍交叉验证下优于最先进的病变回忆和病变F1评分。此外，我们进一步测试我们在多发性硬化症病变数据集上的预训练模型，其中30名受试者处于跨中心评估。结果表明，聚合模型在学习多尺度空间信息方面是有效的。

##### URL
[http://arxiv.org/abs/1807.05153](http://arxiv.org/abs/1807.05153)

##### PDF
[http://arxiv.org/pdf/1807.05153](http://arxiv.org/pdf/1807.05153)

