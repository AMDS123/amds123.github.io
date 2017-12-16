---
layout: post
title: "An All-in-One Network for Dehazing and Beyond"
date: 2017-07-20 14:30:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Boyi Li, Xiulian Peng, Zhangyang Wang, Jizheng Xu, Dan Feng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an image dehazing model built with a convolutional neural network (CNN), called All-in-One Dehazing Network (AOD-Net). It is designed based on a re-formulated atmospheric scattering model. Instead of estimating the transmission matrix and the atmospheric light separately as most previous models did, AOD-Net directly generates the clean image through a light-weight CNN. Such a novel end-to-end design makes it easy to embed AOD-Net into other deep models, e.g., Faster R-CNN, for improving high-level task performance on hazy images. Experimental results on both synthesized and natural hazy image datasets demonstrate our superior performance than the state-of-the-art in terms of PSNR, SSIM and the subjective visual quality. Furthermore, when concatenating AOD-Net with Faster R-CNN and training the joint pipeline from end to end, we witness a large improvement of the object detection performance on hazy images.

##### Abstract (translated by Google)
本文提出了一种利用卷积神经网络（CNN）建立的图像去雾模型，称为AOD-Net（All-in-One Dehazing Network）。它是基于重新制定的大气散射模型而设计的。 AOD-Net不像大多数以前的型号那样分别估算传输矩阵和大气光，而是通过轻量级的CNN直接生成清晰的图像。这种新颖的端到端设计使得将AOD-Net嵌入到其他深度模型（例如，更快的R-CNN）中变得容易，用于改善模糊图像上的高级任务性能。在合成和自然模糊图像数据集上的实验结果表明，我们在PSNR，SSIM和主观视觉质量方面优于现有技术。此外，在将AOD-Net与更快的R-CNN连接在一起并对端到端进行联合管道训练时，我们看到了在朦胧图像上的目标检测性能的大幅提高。

##### URL
[https://arxiv.org/abs/1707.06543](https://arxiv.org/abs/1707.06543)

##### PDF
[https://arxiv.org/pdf/1707.06543](https://arxiv.org/pdf/1707.06543)

