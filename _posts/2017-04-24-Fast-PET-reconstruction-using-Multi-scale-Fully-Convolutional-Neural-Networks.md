---
layout: post
title: "Fast PET reconstruction using Multi-scale Fully Convolutional Neural Networks"
date: 2017-04-24 14:09:22
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Jieqing Jiao, Sebastien Ourselin
mathjax: true
---

* content
{:toc}

##### Abstract
Reconstruction of PET images is an ill-posed inverse problem and often requires iterative algorithms to achieve good image quality for reliable clinical use in practice, at huge computational costs. In this paper, we consider the PET reconstruction a dense prediction problem where the large scale contextual information is essential, and propose a novel architecture of multi-scale fully convolutional neural networks (msfCNN) for fast PET image reconstruction. The proposed msfCNN gains large receptive fields with both memory and computational efficiency, by using a downscaling-upscaling structure and dilated convolutions. Instead of pooling and deconvolution, we propose to use the periodic shuffling operation from sub-pixel convolution and its inverse to scale the size of feature maps without losing resolution. Residual connections were added to improve training. We trained the proposed msfCNN model with simulated data, and applied it to clinical PET data acquired on a Siemens mMR scanner. The results from real oncological and neurodegenerative cases show that the proposed msfCNN-based reconstruction outperforms the iterative approaches in terms of computational time while achieving comparable image quality for quantification. The proposed msfCNN model can be applied to other dense prediction tasks, and fast msfCNN-based PET reconstruction could facilitate the potential use of molecular imaging in interventional/surgical procedures, where cancer surgery can particularly benefit.

##### Abstract (translated by Google)
PET图像的重建是一个不适定的逆问题，并且往往需要迭代算法来实现良好的图像质量，以便在实践中可靠的临床应用，并且计算成本巨大。在本文中，我们认为PET重构是一个密集的预测问题，其中大规模的上下文信息是必不可少的，并提出了一种新的多尺度全卷积神经网络（msfCNN）体系结构，用于快速PET图像重建。所提出的msfCNN通过使用降尺度放大结构和扩张卷积来获得具有记忆和计算效率的大容量接收场。我们建议使用子像素卷积及其反向的周期性混洗操作来缩放特征映射的大小而不会损失分辨率，而不是混合和去卷积。增加了残余连接以改善训练。我们使用模拟数据训练了建议的msfCNN模型，并将其应用于西门子mMR扫描仪上获取的临床PET数据。实际的肿瘤和神经退化病例的结果表明，所提出的基于msfCNN的重建在计算时间方面优于迭代方法，同时实现可比较的图像质量进行量化。所提出的msfCNN模型可以应用于其他密集的预测任务，基于msfCNN的快速PET重建可以促进分子成像在介入/手术过程中的潜在应用，其中癌症手术可以特别有益。

##### URL
[https://arxiv.org/abs/1704.07244](https://arxiv.org/abs/1704.07244)

##### PDF
[https://arxiv.org/pdf/1704.07244](https://arxiv.org/pdf/1704.07244)

