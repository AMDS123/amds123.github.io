---
layout: post
title: "Detecting Small, Densely Distributed Objects with Filter-Amplifier Networks and Loss Boosting"
date: 2018-02-21 23:17:36
categories: arXiv_CV
tags: arXiv_CV Detection
author: Zhenhua Chen, David Crandall, Robert Templeman
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting small, densely distributed objects is a significant challenge: small objects often contain less distinctive information compared to larger ones, and finer-grained precision of bounding box boundaries are required. In this paper, we propose two techniques for addressing this problem. First, we estimate the likelihood that each pixel belongs to an object boundary rather than predicting coordinates of bounding boxes (as YOLO, Faster-RCNN and SSD do), by proposing a new architecture called Filter-Amplifier Networks (FANs). Second, we introduce a technique called Loss Boosting (LB) which attempts to soften the loss imbalance problem on each image. We test our algorithm on the problem of detecting electrical components on a new, realistic, diverse dataset of printed circuit boards (PCBs), as well as the problem of detecting vehicles in the Vehicle Detection in Aerial Imagery (VEDAI) dataset. 
 Experiments show that our method works significantly better than current state-of-the-art algorithms with respect to accuracy, recall and average IoU.

##### Abstract (translated by Google)
检测小的，密集分布的对象是一个重大挑战：与较大的对象相比，小对象通常包含较少的独特信息，并且需要更精细的边界框边界。在本文中，我们提出了两种解决这个问题的技术。首先，我们通过提出一种称为滤波放大器网络（FAN）的新架构来估计每个像素属于对象边界的可能性，而不是预测边界框的坐标（如YOLO，Faster-RCNN和SSD）。其次，我们介绍一种称为损失增强（Loss Boosting，LB）的技术，试图减轻每幅图像上的损失不平衡问题。我们在检测印刷电路板（PCB）的新的，现实的，不同的数据集上检测电子元件的问题上测试了我们的算法，以及在航空影像中的车辆检测（VEDAI）数据集中检测车辆的问题。
 实验表明，我们的方法在准确性，召回率和平均IoU方面比当前最先进的算法工作得更好。

##### URL
[http://arxiv.org/abs/1802.07845](http://arxiv.org/abs/1802.07845)

##### PDF
[http://arxiv.org/pdf/1802.07845](http://arxiv.org/pdf/1802.07845)

