---
layout: post
title: "Fast Disparity Estimation using Dense Networks"
date: 2018-05-19 03:15:12
categories: arXiv_RO
tags: arXiv_RO CNN
author: Rowel Atienza
mathjax: true
---

* content
{:toc}

##### Abstract
Disparity estimation is a difficult problem in stereo vision because the correspondence technique fails in images with textureless and repetitive regions. Recent body of work using deep convolutional neural networks (CNN) overcomes this problem with semantics. Most CNN implementations use an autoencoder method; stereo images are encoded, merged and finally decoded to predict the disparity map. In this paper, we present a CNN implementation inspired by dense networks to reduce the number of parameters. Furthermore, our approach takes into account semantic reasoning in disparity estimation. Our proposed network, called DenseMapNet, is compact, fast and can be trained end-to-end. DenseMapNet requires 290k parameters only and runs at 30Hz or faster on color stereo images in full resolution. Experimental results show that DenseMapNet accuracy is comparable with other significantly bigger CNN-based methods.

##### Abstract (translated by Google)
视差估计是立体视觉中的难题，因为对应技术在具有无纹理和重复区域的图像中失败。最近使用深度卷积神经网络（CNN）的工作主体通过语义克服了这个问题。大多数CNN实现使用自动编码器方法;立体图像被编码，合并并最终解码以预测视差图。在本文中，我们提出了一个受稠密网络启发的CNN实现，以减少参数数量。此外，我们的方法考虑了视差估计中的语义推理。我们提出的称为DenseMapNet的网络紧凑，速度快，可以进行端到端的培训。 DenseMapNet只需要290k参数，在全分辨率的彩色立体图像上以30Hz或更快速度运行。实验结果表明，DenseMapNet精度与其他更大的基于CNN的方法相当。

##### URL
[http://arxiv.org/abs/1805.07499](http://arxiv.org/abs/1805.07499)

##### PDF
[http://arxiv.org/pdf/1805.07499](http://arxiv.org/pdf/1805.07499)

