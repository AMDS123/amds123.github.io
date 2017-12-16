---
layout: post
title: "Learning Normalized Inputs for Iterative Estimation in Medical Image Segmentation"
date: 2017-02-16 22:10:37
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Prediction
author: Michal Drozdzal, Gabriel Chartrand, Eugene Vorontsov, Lisa Di Jorio, An Tang, Adriana Romero, Yoshua Bengio, Chris Pal, Samuel Kadoury
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a simple, yet powerful pipeline for medical image segmentation that combines Fully Convolutional Networks (FCNs) with Fully Convolutional Residual Networks (FC-ResNets). We propose and examine a design that takes particular advantage of recent advances in the understanding of both Convolutional Neural Networks as well as ResNets. Our approach focuses upon the importance of a trainable pre-processing when using FC-ResNets and we show that a low-capacity FCN model can serve as a pre-processor to normalize medical input data. In our image segmentation pipeline, we use FCNs to obtain normalized images, which are then iteratively refined by means of a FC-ResNet to generate a segmentation prediction. As in other fully convolutional approaches, our pipeline can be used off-the-shelf on different image modalities. We show that using this pipeline, we exhibit state-of-the-art performance on the challenging Electron Microscopy benchmark, when compared to other 2D methods. We improve segmentation results on CT images of liver lesions, when contrasting with standard FCN methods. Moreover, when applying our 2D pipeline on a challenging 3D MRI prostate segmentation challenge we reach results that are competitive even when compared to 3D methods. The obtained results illustrate the strong potential and versatility of the pipeline by achieving highly accurate results on multi-modality images from different anatomical regions and organs.

##### Abstract (translated by Google)
在本文中，我们介绍了一个简单而强大的医用图像分割流水线，它将完全卷积网络（FCNs）和全卷积剩余网络（FC-ResNets）相结合。我们提出并研究了一个设计，该设计特别利用了对卷积神经网络和ResNet的理解方面的最新进展。我们的方法侧重于使用FC-ResNets进行可训练预处理的重要性，并且我们表明低容量FCN模型可以作为预处理器来规范医疗输入数据。在我们的图像分割流水线中，我们使用FCNs来获得归一化的图像，然后通过FC-ResNet迭代地改进以生成分割预测。与其他全卷积方法一样，我们的管线可以在不同的图像模式下使用现成的。我们展示了使用这种管道，与其他2D方法相比，我们展示了具有挑战性的电子显微镜基准测试的最新性能。与标准FCN方法相比，我们改善了肝脏病灶CT图像的分割结果。而且，当在具有挑战性的3D MRI前列腺分割挑战中应用我们的2D管线时，即使与3D方法相比，我们也能获得具有竞争力的结果。所获得的结果通过对来自不同解剖区域和器官的多模式图像实现高度精确的结果来说明管道的强大潜力和多功能性。

##### URL
[https://arxiv.org/abs/1702.05174](https://arxiv.org/abs/1702.05174)

##### PDF
[https://arxiv.org/pdf/1702.05174](https://arxiv.org/pdf/1702.05174)

