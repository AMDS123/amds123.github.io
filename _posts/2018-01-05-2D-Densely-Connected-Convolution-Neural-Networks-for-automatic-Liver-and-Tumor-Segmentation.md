---
layout: post
title: "2D-Densely Connected Convolution Neural Networks for automatic Liver and Tumor Segmentation"
date: 2018-01-05 12:30:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Krishna Chaitanya Kaluva, Mahendra Khened, Avinash Kori, Ganapathy Krishnamurthi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a fully automatic 2-stage cascaded approach for segmentation of liver and its tumors in CT (Computed Tomography) images using densely connected fully convolutional neural network (DenseNet). We independently train liver and tumor segmentation models and cascade them for a combined segmentation of the liver and its tumor. The first stage involves segmentation of liver and the second stage uses the first stage's segmentation results for localization of liver and henceforth tumor segmentations inside liver region. The liver model was trained on the down-sampled axial slices $(256 \times 256)$, whereas for the tumor model no down-sampling of slices was done, but instead it was trained on the CT axial slices windowed at three different Hounsfield (HU) levels. On the test set our model achieved a global dice score of 0.923 and 0.625 on liver and tumor respectively. The computed tumor burden had an rmse of 0.044.

##### Abstract (translated by Google)
在本文中，我们提出了一种全自动的2阶段级联方法，用于使用密集连接的完全卷积神经网络（DenseNet）在CT（计算机断层摄影）图像中对肝脏及其肿瘤进行分割。我们独立地训练肝脏和肿瘤分割模型并将它们级联起来，以便对肝脏和肿瘤进行组合分割。第一阶段涉及肝脏的分割，第二阶段使用第一阶段的分割结果来定位肝脏以及此后在肝脏内的肿瘤分割。在下采样的轴向切片（256×256）上训练肝脏模型，而对于肿瘤模型，切片没有下降采样，而是在三个不同的Hounsfield窗口的CT轴向切片上进行训练（HU）水平。在测试集上，我们的模型分别在肝脏和肿瘤上获得了0.923和0.625的全局骰子评分。计算的肿瘤负荷具有0.044的rmse。

##### URL
[https://arxiv.org/abs/1802.02182](https://arxiv.org/abs/1802.02182)

##### PDF
[https://arxiv.org/pdf/1802.02182](https://arxiv.org/pdf/1802.02182)

