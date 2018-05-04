---
layout: post
title: "On the iterative refinement of densely connected representation levels for semantic segmentation"
date: 2018-04-30 17:26:49
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Arantxa Casanova, Guillem Cucurull, Michal Drozdzal, Adriana Romero, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art semantic segmentation approaches increase the receptive field of their models by using either a downsampling path composed of poolings/strided convolutions or successive dilated convolutions. However, it is not clear which operation leads to best results. In this paper, we systematically study the differences introduced by distinct receptive field enlargement methods and their impact on the performance of a novel architecture, called Fully Convolutional DenseResNet (FC-DRN). FC-DRN has a densely connected backbone composed of residual networks. Following standard image segmentation architectures, receptive field enlargement operations that change the representation level are interleaved among residual networks. This allows the model to exploit the benefits of both residual and dense connectivity patterns, namely: gradient flow, iterative refinement of representations, multi-scale feature combination and deep supervision. In order to highlight the potential of our model, we test it on the challenging CamVid urban scene understanding benchmark and make the following observations: 1) downsampling operations outperform dilations when the model is trained from scratch, 2) dilations are useful during the finetuning step of the model, 3) coarser representations require less refinement steps, and 4) ResNets (by model construction) are good regularizers, since they can reduce the model capacity when needed. Finally, we compare our architecture to alternative methods and report state-of-the-art result on the Camvid dataset, with at least twice fewer parameters.

##### Abstract (translated by Google)
最先进的语义分割方法通过使用由汇集/跨度卷积或连续扩张卷积组成的下采样路径来增加其模型的接受场。但是，目前尚不清楚哪种操作能够产生最佳结果。在本文中，我们系统地研究了不同的接收场扩大方法所引入的差异以及它们对称为完全卷积密集网（FC-DRN）的新型架构的性能的影响。 FC-DRN具有由残余网络组成的密集连接主干。遵循标准图像分割体系结构，改变表示级别的接受域扩大操作在残余网络中交织。这允许模型利用残差和密集连通性模式的优点，即：梯度流，表示的迭代优化，多尺度特征组合和深度监督。为了突出我们模型的潜力，我们在具有挑战性的CamVid城市场景理解基准上进行了测试，并进行了以下观察：1）当从头开始训练模型时，降采样操作的性能优于膨胀量; 2）在微调步骤中， 3）较粗糙的表示需要较少的细化步骤，以及4）ResNets（通过模型构建）是良好的正则化器，因为它们可以在需要时降低模型容量。最后，我们将我们的体系结构与其他方法进行比较，并报告Camvid数据集的最新结果，并至少减少两次参数。

##### URL
[https://arxiv.org/abs/1804.11332](https://arxiv.org/abs/1804.11332)

##### PDF
[https://arxiv.org/pdf/1804.11332](https://arxiv.org/pdf/1804.11332)

