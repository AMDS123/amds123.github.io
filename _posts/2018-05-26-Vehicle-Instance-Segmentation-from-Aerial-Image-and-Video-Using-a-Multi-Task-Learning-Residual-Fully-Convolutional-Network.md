---
layout: post
title: "Vehicle Instance Segmentation from Aerial Image and Video Using a Multi-Task Learning Residual Fully Convolutional Network"
date: 2018-05-26 13:56:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Deep_Learning Detection
author: Lichao Mou, Xiao Xiang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection and semantic segmentation are two main themes in object retrieval from high-resolution remote sensing images, which have recently achieved remarkable performance by surfing the wave of deep learning and, more notably, convolutional neural networks (CNNs). In this paper, we are interested in a novel, more challenging problem of vehicle instance segmentation, which entails identifying, at a pixel-level, where the vehicles appear as well as associating each pixel with a physical instance of a vehicle. In contrast, vehicle detection and semantic segmentation each only concern one of the two. We propose to tackle this problem with a semantic boundary-aware multi-task learning network. More specifically, we utilize the philosophy of residual learning (ResNet) to construct a fully convolutional network that is capable of harnessing multi-level contextual feature representations learned from different residual blocks. We theoretically analyze and discuss why residual networks can produce better probability maps for pixel-wise segmentation tasks. Then, based on this network architecture, we propose a unified multi-task learning network that can simultaneously learn two complementary tasks, namely, segmenting vehicle regions and detecting semantic boundaries. The latter subproblem is helpful for differentiating closely spaced vehicles, which are usually not correctly separated into instances. Currently, datasets with pixel-wise annotation for vehicle extraction are ISPRS dataset and IEEE GRSS DFC2015 dataset over Zeebrugge, which specializes in semantic segmentation. Therefore, we built a new, more challenging dataset for vehicle instance segmentation, called the Busy Parking Lot UAV Video dataset, and we make our dataset available at <a href="http://www.sipeo.bgu.tum.de/download">this http URL</a> so that it can be used to benchmark future vehicle instance segmentation algorithms.

##### Abstract (translated by Google)
目标检测和语义分割是高分辨率遥感图像对象检索的两个主要主题，最近通过浏览深度学习波，尤其是卷积神经网络（CNN），取得了显着的性能。在本文中，我们感兴趣的是一个新颖，更具挑战性的车辆实例分割问题，它需要在像素级别识别车辆出现的位置，并将每个像素与车辆的物理实例相关联。相比之下，车辆检测和语义分割只涉及两者之一。我们提出用语义边界感知多任务学习网络来解决这个问题。更具体地说，我们利用残差学习（ResNet）的思想来构建一个完全卷积网络，该网络能够利用从不同残差块学习到的多级上下文特征表示。我们从理论上分析和讨论为什么残余网络可以为像素分割任务生成更好的概率图。然后，基于这种网络架构，我们提出了一个统一的多任务学习网络，可以同时学习两个互补的任务，即分割车辆区域和检测语义边界。后一个子问题有助于区分紧密间隔的车辆，这些车辆通常没有正确分离成实例。目前，用于车辆提取的具有逐像素注释的数据集是Zesebrugge上的ISPRS数据集和IEEE GRSS DFC2015数据集，专门用于语义分割。因此，我们为车辆实例分割建立了一个新的，更具挑战性的数据集，称为Busy Parking Lot无人机视频数据集，并且我们可以在<a href =“http://www.sipeo.bgu.tum.de/上提供我们的数据集。下载“>这个http URL </a>，以便它可以用于基准未来的车辆实例分段算法。

##### URL
[http://arxiv.org/abs/1805.10485](http://arxiv.org/abs/1805.10485)

##### PDF
[http://arxiv.org/pdf/1805.10485](http://arxiv.org/pdf/1805.10485)

