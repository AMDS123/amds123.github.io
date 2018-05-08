---
layout: post
title: "VH-HFCN based Parking Slot and Lane Markings Segmentation on Panoramic Surround View"
date: 2018-05-07 02:20:04
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Yan Wu, Tao Yang, Junqiao Zhao, Linting Guan, Wei Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
The automatic parking is being massively developed by car manufacturers and providers. Until now, there are two problems with the automatic parking. First, there is no openly-available segmentation labels of parking slot on panoramic surround view (PSV) dataset. Second, how to detect parking slot and road structure robustly. Therefore, in this paper, we build up a public PSV dataset. At the same time, we proposed a highly fused convolutional network (HFCN) based segmentation method for parking slot and lane markings based on the PSV dataset. A surround-view image is made of four calibrated images captured from four fisheye cameras. We collect and label more than 4,200 surround view images for this task, which contain various illuminated scenes of different types of parking slots. A VH-HFCN network is proposed, which adopts an HFCN as the base, with an extra efficient VH-stage for better segmenting various markings. The VH-stage consists of two independent linear convolution paths with vertical and horizontal convolution kernels respectively. This modification enables the network to robustly and precisely extract linear features. We evaluated our model on the PSV dataset and the results showed outstanding performance in ground markings segmentation. Based on the segmented markings, parking slots and lanes are acquired by skeletonization, hough line transform and line arrangement.

##### Abstract (translated by Google)
自动停车正在由汽车制造商和供应商大规模开发。到目前为止，自动泊车有两个问题。首先，在全景环绕视图（PSV）数据集上没有可公开使用的停车位的分段标签。其次，如何稳健地检测停车位和道路结构。因此，在本文中，我们构建了一个公共PSV数据集。同时，我们基于PSV数据集提出了一种基于高融合卷积网络（HFCN）的停车位和车道标线分割方法。环视图像由四个鱼眼相机拍摄的四个校准图像组成。我们为此任务收集并标记了4,200多幅环视图像，其中包含不同类型停车位的各种照明场景。提出了一种VH-HFCN网络，其采用HFCN作为基础，具有更高效的VH级以更好地分割各种标记。 VH级包含两个独立的线性卷积路径，分别具有垂直和水平卷积核。这种修改使网络能够稳健并精确地提取线性特征。我们在PSV数据集上评估了我们的模型，结果显示在地面标记分割中表现出色。基于分段标记，通过骨架化，霍夫线变换和线排列来获得停车位和车道。

##### URL
[http://arxiv.org/abs/1804.07027](http://arxiv.org/abs/1804.07027)

##### PDF
[http://arxiv.org/pdf/1804.07027](http://arxiv.org/pdf/1804.07027)

