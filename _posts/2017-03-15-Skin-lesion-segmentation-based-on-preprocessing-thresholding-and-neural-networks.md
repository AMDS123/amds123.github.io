---
layout: post
title: "Skin lesion segmentation based on preprocessing, thresholding and neural networks"
date: 2017-03-15 00:15:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Juana M. Gutiérrez-Arriola, Marta Gómez-Álvarez, Victor Osma-Ruiz, Nicolás Sáenz-Lechón, Rubén Fraile
mathjax: true
---

* content
{:toc}

##### Abstract
This abstract describes the segmentation system used to participate in the challenge ISIC 2017: Skin Lesion Analysis Towards Melanoma Detection. Several preprocessing techniques have been tested for three color representations (RGB, YCbCr and HSV) of 392 images. Results have been used to choose the better preprocessing for each channel. In each case a neural network is trained to predict the Jaccard Index based on object characteristics. The system includes black frames and reference circle detection algorithms but no special treatment is done for hair removal. Segmentation is performed in two steps first the best channel to be segmented is chosen by selecting the best neural network output. If this output does not predict a Jaccard Index over 0.5 a more aggressive preprocessing is performed using open and close morphological operations and the segmentation of the channel that obtains the best output from the neural networks is selected as the lesion.

##### Abstract (translated by Google)
本摘要描述了用于参与“ISIC 2017年挑战：黑素瘤检测皮肤病变分析”的分类系统。已经针对392个图像的三种颜色表示（RGB，YCbCr和HSV）测试了几种预处理技术。已经使用结果来为每个通道选择更好的预处理。在每种情况下，训练一个神经网络来预测基于对象特性的Jaccard指数。该系统包括黑色的框架和参考圆检测算法，但没有特别的处理是做脱毛。首先通过选择最佳神经网络输出来选择要分割的最佳信道，分两步进行分割。如果该输出不能预测超过0.5的Jaccard指数，则使用开放和紧密的形态学操作执行更积极的预处理，并且将从神经网络获得最佳输出的通道的分割选择为病变。

##### URL
[https://arxiv.org/abs/1703.04845](https://arxiv.org/abs/1703.04845)

##### PDF
[https://arxiv.org/pdf/1703.04845](https://arxiv.org/pdf/1703.04845)

