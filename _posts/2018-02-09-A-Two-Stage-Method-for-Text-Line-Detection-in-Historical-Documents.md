---
layout: post
title: "A Two-Stage Method for Text Line Detection in Historical Documents"
date: 2018-02-09 16:52:17
categories: arXiv_CV
tags: arXiv_CV Prediction Detection
author: Tobias Gr&#xfc;ning, Gundram Leifert, Tobias Strau&#xdf;, Roger Labahn
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a two-stage text line detection method for historical documents. In a first stage, a deep neural network called ARU-Net labels pixels to belong to one of the three classes: baseline, separator or other. The separator class marks beginning and end of each text line. The ARU-Net is trainable from scratch with manageably few manually annotated example images (less than 50). This is achieved by utilizing data augmentation strategies. The network predictions are used as input for the second stage which performs a bottom-up clustering to build baselines. The developed method is capable of handling complex layouts as well as curved and arbitrarily oriented text lines. It substantially outperforms current state-of-the-art approaches. For example, for the complex track of the cBAD: ICDAR2017 Competiton on Baseline Detection the F-value is increased from 0.859 to 0.922. The framework to train and run the ARU-Net is open source.

##### Abstract (translated by Google)
这项工作提出了一个两阶段的历史文件的文本行检测方法。在第一阶段，称为ARU-Net的深度神经网络将像素标记为属于三个类别之一：基线，分隔符或其他类别。分隔符类标记每个文本行的开始和结束。 ARU-Net可以从头开始训练，只需少量手动注释的示例图像（小于50）。这是通过利用数据增强策略实现的。网络预测被用作第二阶段的输入，其执行自下而上的聚类来构建基线。所开发的方法能够处理复杂的布局以及曲线和任意方向的文本行。它远远超过当前最先进的方法。例如，对于cBAD的复杂轨迹：ICDAR2017竞争基线检测，F值从0.859增加到0.922。培训和运行ARU-Net的框架是开源的。

##### URL
[http://arxiv.org/abs/1802.03345](http://arxiv.org/abs/1802.03345)

##### PDF
[http://arxiv.org/pdf/1802.03345](http://arxiv.org/pdf/1802.03345)

