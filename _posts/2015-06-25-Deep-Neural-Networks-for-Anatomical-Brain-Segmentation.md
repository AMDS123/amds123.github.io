---
layout: post
title: "Deep Neural Networks for Anatomical Brain Segmentation"
date: 2015-06-25 16:19:44
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation
author: Alexandre de Brebisson, Giovanni Montana
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach to automatically segment magnetic resonance (MR) images of the human brain into anatomical regions. Our methodology is based on a deep artificial neural network that assigns each voxel in an MR image of the brain to its corresponding anatomical region. The inputs of the network capture information at different scales around the voxel of interest: 3D and orthogonal 2D intensity patches capture the local spatial context while large, compressed 2D orthogonal patches and distances to the regional centroids enforce global spatial consistency. Contrary to commonly used segmentation methods, our technique does not require any non-linear registration of the MR images. To benchmark our model, we used the dataset provided for the MICCAI 2012 challenge on multi-atlas labelling, which consists of 35 manually segmented MR images of the brain. We obtained competitive results (mean dice coefficient 0.725, error rate 0.163) showing the potential of our approach. To our knowledge, our technique is the first to tackle the anatomical segmentation of the whole brain using deep neural networks.

##### Abstract (translated by Google)
我们提出了一种新的方法来自动将人脑的磁共振（MR）图像分割成解剖区域。我们的方法基于深度人工神经网络，将大脑的MR图像中的每个体素分配给其对应的解剖区域。在感兴趣体素周围的不同尺度上的网络捕获信息的输入：3D和正交2D强度片捕获局部空间上下文，而大的，压缩的2D正交片和到区域质心的距离强制全局空间一致性。与常用的分割方法相反，我们的技术不需要MR图像的任何非线性配准。为了对我们的模型进行基准测试，我们使用了为MICCAI 2012提供的多图集标注提供的数据集，其中包含35个手动分割的大脑MR图像。我们获得了竞争结果（平均模子系数0.725，错误率0.163），显示了我们的方法的潜力。据我们所知，我们的技术是第一个使用深度神经网络解决整个大脑的解剖分割。

##### URL
[https://arxiv.org/abs/1502.02445](https://arxiv.org/abs/1502.02445)

##### PDF
[https://arxiv.org/pdf/1502.02445](https://arxiv.org/pdf/1502.02445)

