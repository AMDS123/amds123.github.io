---
layout: post
title: "Multi-level Wavelet-CNN for Image Restoration"
date: 2018-05-18 06:59:00
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse CNN
author: Pengju Liu, Hongzhi Zhang, Kai Zhang, Liang Lin, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
The tradeoff between receptive field size and efficiency is a crucial issue in low level vision. Plain convolutional networks (CNNs) generally enlarge the receptive field at the expense of computational cost. Recently, dilated filtering has been adopted to address this issue. But it suffers from gridding effect, and the resulting receptive field is only a sparse sampling of input image with checkerboard patterns. In this paper, we present a novel multi-level wavelet CNN (MWCNN) model for better tradeoff between receptive field size and computational efficiency. With the modified U-Net architecture, wavelet transform is introduced to reduce the size of feature maps in the contracting subnetwork. Furthermore, another convolutional layer is further used to decrease the channels of feature maps. In the expanding subnetwork, inverse wavelet transform is then deployed to reconstruct the high resolution feature maps. Our MWCNN can also be explained as the generalization of dilated filtering and subsampling, and can be applied to many image restoration tasks. The experimental results clearly show the effectiveness of MWCNN for image denoising, single image super-resolution, and JPEG image artifacts removal.

##### Abstract (translated by Google)
接受领域大小和效率之间的权衡是低级视觉中的关键问题。平原卷积网络（CNN）通常以牺牲计算成本为代价来扩大接受范围。最近，已经采用扩张过滤来解决这个问题。但它受到网格效应的影响，并且由此产生的接受域仅仅是具有棋盘图案的输入图像的稀疏采样。在本文中，我们提出了一种新颖的多级小波CNN（MWCNN）模型，用于更好地权衡感受野大小和计算效率之间的折衷。通过改进的U-Net架构，引入小波变换来缩小签约子网络中的特征映射的大小。此外，另一个卷积层还用于减少特征映射的通道。在扩展子网络中，部署逆小波变换来重建高分辨率特征地图。我们的MWCNN也可以解释为扩张滤波和二次采样的泛化，并且可以应用于许多图像恢复任务。实验结果清楚地表明了MWCNN对图像去噪，单幅图像超分辨率和JPEG图像伪像去除的有效性。

##### URL
[http://arxiv.org/abs/1805.07071](http://arxiv.org/abs/1805.07071)

##### PDF
[http://arxiv.org/pdf/1805.07071](http://arxiv.org/pdf/1805.07071)

