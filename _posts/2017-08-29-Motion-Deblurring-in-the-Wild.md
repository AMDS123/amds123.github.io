---
layout: post
title: "Motion Deblurring in the Wild"
date: 2017-08-29 13:51:31
categories: arXiv_CV
tags: arXiv_CV CNN
author: Mehdi Noroozi, Paramanand Chandramouli, Paolo Favaro
mathjax: true
---

* content
{:toc}

##### Abstract
The task of image deblurring is a very ill-posed problem as both the image and the blur are unknown. Moreover, when pictures are taken in the wild, this task becomes even more challenging due to the blur varying spatially and the occlusions between the object. Due to the complexity of the general image model we propose a novel convolutional network architecture which directly generates the sharp image.This network is built in three stages, and exploits the benefits of pyramid schemes often used in blind deconvolution. One of the main difficulties in training such a network is to design a suitable dataset. While useful data can be obtained by synthetically blurring a collection of images, more realistic data must be collected in the wild. To obtain such data we use a high frame rate video camera and keep one frame as the sharp image and frame average as the corresponding blurred image. We show that this realistic dataset is key in achieving state-of-the-art performance and dealing with occlusions.

##### Abstract (translated by Google)
图像去模糊的任务是一个非常不适合的问题，因为图像和模糊都是未知的。而且，当在野外拍摄照片时，由于空间上变化的模糊和对象之间的遮挡，这个任务变得更具挑战性。由于一般图像模型的复杂性，我们提出了一种新的卷积网络体系结构，可以直接生成清晰的图像。该网络分三个阶段构建，充分利用了传统的盲卷去卷积算法的优点。培训这种网络的主要困难之一是设计一个合适的数据集。尽管可以通过综合模糊图像集合来获得有用的数据，但是更真实的数据必须在野外收集。为了获得这样的数据，我们使用高帧频摄像机，并保留一帧作为相应模糊图像的清晰图像和帧平均值。我们表明，这个现实的数据集是实现最先进的性能和处理遮挡的关键。

##### URL
[https://arxiv.org/abs/1701.01486](https://arxiv.org/abs/1701.01486)

##### PDF
[https://arxiv.org/pdf/1701.01486](https://arxiv.org/pdf/1701.01486)

