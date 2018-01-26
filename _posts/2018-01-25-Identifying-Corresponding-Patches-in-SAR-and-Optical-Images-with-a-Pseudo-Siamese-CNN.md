---
layout: post
title: "Identifying Corresponding Patches in SAR and Optical Images with a Pseudo-Siamese CNN"
date: 2018-01-25 16:12:38
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Lloyd H. Hughes, Michael Schmitt, Lichao Mou, Yuanyuan Wang, Xiao Xiang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In this letter, we propose a pseudo-siamese convolutional neural network (CNN) architecture that enables to solve the task of identifying corresponding patches in very-high-resolution (VHR) optical and synthetic aperture radar (SAR) remote sensing imagery. Using eight convolutional layers each in two parallel network streams, a fully connected layer for the fusion of the features learned in each stream, and a loss function based on binary cross-entropy, we achieve a one-hot indication if two patches correspond or not. The network is trained and tested on an automatically generated dataset that is based on a deterministic alignment of SAR and optical imagery via previously reconstructed and subsequently co-registered 3D point clouds. The satellite images, from which the patches comprising our dataset are extracted, show a complex urban scene containing many elevated objects (i.e. buildings), thus providing one of the most difficult experimental environments. The achieved results show that the network is able to predict corresponding patches with high accuracy, thus indicating great potential for further development towards a generalized multi-sensor key-point matching procedure. Index Terms-synthetic aperture radar (SAR), optical imagery, data fusion, deep learning, convolutional neural networks (CNN), image matching, deep matching

##### Abstract (translated by Google)
在这封信中，我们提出了一种伪连体卷积神经网络（CNN）体系结构，能够解决在甚高分辨率（VHR）光学和合成孔径雷达（SAR）遥感图像中识别相应片的任务。在两个并行网络流中使用八个卷积层，用于融合在每个流中学习的特征的完全连接层以及基于二元交叉熵的损失函数，如果两个补丁对应，则实现单热指示。该网络在自动生成的数据集上进行训练和测试，该数据集基于SAR和光学图像的确定性对齐，通过先前重建并随后共同注册的三维点云。从中提取包括我们的数据集的贴片的卫星图像示出了包含许多升高的物体（即建筑物）的复杂的城市场景，从而提供了最困难的实验环境之一。实验结果表明，该网络能够以较高的精度预测相应的补丁，为进一步发展广义多传感器关键点匹配程序提供了巨大的潜力。关键词：合成孔径雷达（SAR），光学图像，数据融合，深度学习，卷积神经网络（CNN），图像匹配，深度匹配

##### URL
[http://arxiv.org/abs/1801.08467](http://arxiv.org/abs/1801.08467)

##### PDF
[http://arxiv.org/pdf/1801.08467](http://arxiv.org/pdf/1801.08467)

