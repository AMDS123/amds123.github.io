---
layout: post
title: "REFUGE CHALLENGE 2018-Task 2:Deep Optic Disc and Cup Segmentation in Fundus Images Using U-Net and Multi-scale Feature Matching Networks"
date: 2018-07-30 16:43:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Vivek Kumar Singh, Hatem A. Rashwan, Adel Saleh, Farhan Akram, Md Mostafa Kamal Sarker, Nidhi Pandey, Saddam Abdulwahab
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, an optic disc and cup segmentation method is proposed using U-Net followed by a multi-scale feature matching network. The proposed method targets task 2 of the REFUGE challenge 2018. In order to solve the segmentation problem of task 2, we firstly crop the input image using single shot multibox detector (SSD). The cropped image is then passed to an encoder-decoder network with skip connections also known as generator. Afterwards, both the ground truth and generated images are fed to a convolution neural network (CNN) to extract their multi-level features. A dice loss function is then used to match the features of the two images by minimizing the error at each layer. The aggregation of error from each layer is back-propagated through the generator network to enforce it to generate a segmented image closer to the ground truth. The CNN network improves the performance of the generator network without increasing the complexity of the model.

##### Abstract (translated by Google)
本文利用U-Net和多尺度特征匹配网络提出了一种视盘和杯子分割方法。所提出的方法针对REFUGE挑战2018的任务2.为了解决任务2的分割问题，我们首先使用单发多箱检测器（SSD）来裁剪输入图像。然后将裁剪的图像传递到编码器 - 解码器网络，其中跳过连接也称为生成器。然后，将地面实况和生成的图像都馈送到卷积神经网络（CNN）以提取它们的多级特征。然后使用骰子丢失函数通过最小化每层的误差来匹配两个图像的特征。来自每个层的误差的聚合通过生成器网络反向传播，以强制它生成更接近地面实况的分段图像。 CNN网络在不增加模型复杂性的情况下改善了发电机网络的性能。

##### URL
[http://arxiv.org/abs/1807.11433](http://arxiv.org/abs/1807.11433)

##### PDF
[http://arxiv.org/pdf/1807.11433](http://arxiv.org/pdf/1807.11433)

