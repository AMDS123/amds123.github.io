---
layout: post
title: "Automatic Pixelwise Object Labeling for Aerial Imagery Using Stacked U-Nets"
date: 2018-03-13 17:39:01
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Andrew Khalel, Motaz El-Saban
mathjax: true
---

* content
{:toc}

##### Abstract
Automation of objects labeling in aerial imagery is a computer vision task with numerous practical applications. Fields like energy exploration require an automated method to process a continuous stream of imagery on a daily basis. In this paper we propose a pipeline to tackle this problem using a stack of convolutional neural networks (U-Net architecture) arranged end-to-end. Each network works as post-processor to the previous one. Our model outperforms current state-of-the-art on two different datasets: Inria Aerial Image Labeling dataset and Massachusetts Buildings dataset each with different characteristics such as spatial resolution, object shapes and scales. Moreover, we experimentally validate computation time savings by processing sub-sampled images and later upsampling pixelwise labeling. These savings come at a negligible degradation in segmentation quality. Though the conducted experiments in this paper cover only aerial imagery, the technique presented is general and can handle other types of images.

##### Abstract (translated by Google)
航空影像中物体标记的自动化是一项计算机视觉任务，具有许多实际应用。像能源勘探这样的领域需要一种自动化方法来每天处理连续的图像流。在本文中，我们提出了一个流水线来解决这个问题，使用一堆端到端的卷积神经网络（U-Net架构）。每个网络都作为后一个处理器工作。我们的模型在两个不同的数据集上胜过当前的最新技术：Inria Aerial Image Labeling数据集和Massachusetts Buildings数据集，每个数据集都具有不同的特征，如空间分辨率，物体形状和比例尺。此外，我们通过处理子采样图像和稍后向上采样按像素标记来实验验证计算时间节省。节省的这些资源对分割质量的影响可以忽略不计。虽然本文进行的实验仅涵盖航空影像，但所呈现的技术是通用的并且可以处理其他类型的影像。

##### URL
[http://arxiv.org/abs/1803.04953](http://arxiv.org/abs/1803.04953)

##### PDF
[http://arxiv.org/pdf/1803.04953](http://arxiv.org/pdf/1803.04953)

