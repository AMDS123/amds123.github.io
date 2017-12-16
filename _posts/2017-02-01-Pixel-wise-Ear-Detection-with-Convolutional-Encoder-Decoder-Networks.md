---
layout: post
title: "Pixel-wise Ear Detection with Convolutional Encoder-Decoder Networks"
date: 2017-02-01 15:16:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection Recognition
author: Žiga Emeršič, Luka Lan Gabriel, Vitomir Štruc, Peter Peer
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection and segmentation represents the basis for many tasks in computer and machine vision. In biometric recognition systems the detection of the region-of-interest (ROI) is one of the most crucial steps in the overall processing pipeline, significantly impacting the performance of the entire recognition system. Existing approaches to ear detection, for example, are commonly susceptible to the presence of severe occlusions, ear accessories or variable illumination conditions and often deteriorate in their performance if applied on ear images captured in unconstrained settings. To address these shortcomings, we present in this paper a novel ear detection technique based on convolutional encoder-decoder networks (CEDs). For our technique, we formulate the problem of ear detection as a two-class segmentation problem and train a convolutional encoder-decoder network based on the SegNet architecture to distinguish between image-pixels belonging to either the ear or the non-ear class. The output of the network is then post-processed to further refine the segmentation result and return the final locations of the ears in the input image. Different from competing techniques from the literature, our approach does not simply return a bounding box around the detected ear, but provides detailed, pixel-wise information about the location of the ears in the image. Our experiments on a dataset gathered from the web (a.k.a. in the wild) show that the proposed technique ensures good detection results in the presence of various covariate factors and significantly outperforms the existing state-of-the-art.

##### Abstract (translated by Google)
对象检测和分割代表了计算机和机器视觉中许多任务的基础。在生物识别系统中，感兴趣区域（ROI）的检测是整个处理流程中最关键的步骤之一，显着影响整个识别系统的性能。例如，耳朵检测的现有方法通常容易受到严重遮挡，耳朵附件或可变照明条件的影响，并且如果应用于在不受限制的环境中拍摄的耳朵图像，其性能经常恶化。为了解决这些缺点，本文提出了一种基于卷积编码器 - 解码器网络（CED）的新颖耳检测技术。对于我们的技术，我们将耳朵检测问题作为一个两类分割问题，并且训练一个基于SegNet架构的卷积编码器 - 解码器网络来区分属于耳朵类型还是非耳朵类型的图像像素。然后对网络的输出进行后处理，以进一步细化分割结果并返回输入图像中耳朵的最终位置。与文献中的竞争技术不同，我们的方法不是简单地在检测到的耳朵周围返回边界框，而是提供关于图像中耳朵的位置的详细的像素方面的信息。我们对从网络（又名野外）收集的数据集进行的实验表明，所提出的技术在存在各种协变量因子的情况下确保良好的检测结果，并且明显优于现有技术水平。

##### URL
[https://arxiv.org/abs/1702.00307](https://arxiv.org/abs/1702.00307)

##### PDF
[https://arxiv.org/pdf/1702.00307](https://arxiv.org/pdf/1702.00307)

