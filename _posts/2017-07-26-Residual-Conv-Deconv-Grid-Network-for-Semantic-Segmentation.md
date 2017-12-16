---
layout: post
title: "Residual Conv-Deconv Grid Network for Semantic Segmentation"
date: 2017-07-26 08:18:54
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction
author: Damien Fourure, Rémi Emonet, Elisa Fromont, Damien Muselet, Alain Tremeau, Christian Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents GridNet, a new Convolutional Neural Network (CNN) architecture for semantic image segmentation (full scene labelling). Classical neural networks are implemented as one stream from the input to the output with subsampling operators applied in the stream in order to reduce the feature maps size and to increase the receptive field for the final prediction. However, for semantic image segmentation, where the task consists in providing a semantic class to each pixel of an image, feature maps reduction is harmful because it leads to a resolution loss in the output prediction. To tackle this problem, our GridNet follows a grid pattern allowing multiple interconnected streams to work at different resolutions. We show that our network generalizes many well known networks such as conv-deconv, residual or U-Net networks. GridNet is trained from scratch and achieves competitive results on the Cityscapes dataset.

##### Abstract (translated by Google)
本文提出了GridNet，一种用于语义图像分割（全景标注）的新型卷积神经网络（CNN）体系结构。经典神经网络被实现为从输入到输出的一个流，其中在流中应用子采样算子以便减小特征图大小并增加最终预测的接受场。然而，对于语义图像分割而言，其任务在于为图像的每个像素提供语义类，因此特征映射的减少是有害的，因为其导致输出预测中的分辨率损失。为了解决这个问题，我们的GridNet遵循一个网格模式，允许多个互连的流以不同的分辨率工作。我们表明，我们的网络推广了许多众所周知的网络，如conv-deconv，残余或U-Net网络。 GridNet从零开始训练，并在Cityscapes数据集上获得有竞争力的结果。

##### URL
[https://arxiv.org/abs/1707.07958](https://arxiv.org/abs/1707.07958)

##### PDF
[https://arxiv.org/pdf/1707.07958](https://arxiv.org/pdf/1707.07958)

