---
layout: post
title: "Denoising Auto-encoder with Recurrent Skip Connections and Residual Regression for Music Source Separation"
date: 2018-07-05 08:54:32
categories: arXiv_AI
tags: arXiv_AI GAN CNN
author: Jen-Yu Liu, Yi-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks with skip connections have shown good performance in music source separation. In this work, we propose a denoising Auto-encoder with Recurrent skip Connections (ARC). We use 1D convolution along the temporal axis of the time-frequency feature map in all layers of the fully-convolutional network. The use of 1D convolution makes it possible to apply recurrent layers to the intermediate outputs of the convolution layers. In addition, we also propose an enhancement network and a residual regression method to further improve the separation result. The recurrent skip connections, the enhancement module, and the residual regression all improve the separation quality. The ARC model with residual regression achieves 5.74 siganl-to-distoration ratio (SDR) in vocals with MUSDB in SiSEC 2018. We also evaluate the ARC model alone on the older dataset DSD100 (used in SiSEC 2016) and it achieves 5.91 SDR in vocals.

##### Abstract (translated by Google)
具有跳过连接的卷积神经网络在音乐源分离中表现出良好的性能。在这项工作中，我们提出了一种具有循环跳过连接（ARC）的去噪自动编码器。我们在完全卷积网络的所有层中沿着时频特征图的时间轴使用1D卷积。使用1D卷积使得可以将循环层应用于卷积层的中间输出。此外，我们还提出了增强网络和残差回归方法，以进一步改善分离结果。循环跳过连接，增强模块和残余回归都可以提高分离质量。具有残余回归的ARC模型在SiSEC 2018中使用MUSDB在人声中实现5.74 siganl-to-distoration ratio（SDR）。我们还在旧数据集DSD100（用于SiSEC 2016）中单独评估ARC模型，并且在人声中实现5.91 SDR 。

##### URL
[http://arxiv.org/abs/1807.01898](http://arxiv.org/abs/1807.01898)

##### PDF
[http://arxiv.org/pdf/1807.01898](http://arxiv.org/pdf/1807.01898)

