---
layout: post
title: "Virtual Codec Supervised Re-Sampling Network for Image Compression"
date: 2018-06-22 06:48:07
categories: arXiv_CV
tags: arXiv_CV
author: Lijun Zhao, Huihui Bai, Anhong Wang, Yao Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an image re-sampling compression method by learning virtual codec network (VCN) to resolve the non-differentiable problem of quantization function for image compression. Here, the image re-sampling not only refers to image full-resolution re-sampling but also low-resolution re-sampling. We generalize this method for standard-compliant image compression (SCIC) framework and deep neural networks based compression (DNNC) framework. Specifically, an input image is measured by re-sampling network (RSN) network to get re-sampled vectors. Then, these vectors are directly quantized in the feature space in SCIC, or discrete cosine transform coefficients of these vectors are quantized to further improve coding efficiency in DNNC. At the encoder, the quantized vectors or coefficients are losslessly compressed by arithmetic coding. At the receiver, the decoded vectors are utilized to restore input image by image decoder network (IDN). In order to train RSN network and IDN network together in an end-to-end fashion, our VCN network intimates projection from the re-sampled vectors to the IDN-decoded image. As a result, gradients from IDN network to RSN network can be approximated by VCN network's gradient. Because dimension reduction can be further achieved by quantization in some dimensional space after image re-sampling within auto-encoder architecture, we can well initialize our networks from pre-trained auto-encoder networks. Through extensive experiments and analysis, it is verified that the proposed method has more effectiveness and versatility than many state-of-the-art approaches.

##### Abstract (translated by Google)
在本文中，我们通过学习虚拟编解码网络（VCN）来提出一种图像重采样压缩方法来解决图像压缩量化函数的不可区分问题。这里，图像重新采样不仅涉及图像全分辨率重新采样，而且还涉及低分辨率重新采样。我们将这种方法推广到标准兼容图像压缩（SCIC）框架和基于深度神经网络的压缩（DNNC）框架。具体而言，通过重新采样网络（RSN）网络来测量输入图像以获得重新采样的矢量。然后，将这些矢量直接量化到SCIC中的特征空间中，或者对这些矢量的离散余弦变换系数进行量化，以进一步提高DNNC中的编码效率。在编码器处，量化矢量或系数通过算术编码被无损地压缩。在接收器处，解码矢量被用于通过图像解码器网络（IDN）恢复输入图像。为了以端到端的方式一起训练RSN网络和IDN网络，我们的VCN网络将重新采样的向量投影到IDN解码图像。因此，从IDN网络到RSN网络的梯度可以近似为VCN网络的梯度。因为在自动编码器体系结构中的图像重新采样之后，通过在一些维空间中进行量化可以进一步实现降维，所以我们可以很好地从预先训练的自动编码器网络初始化我们的网络。通过广泛的实验和分析，验证了所提出的方法比许多最先进的方法具有更多的有效性和多样性。

##### URL
[http://arxiv.org/abs/1806.08514](http://arxiv.org/abs/1806.08514)

##### PDF
[http://arxiv.org/pdf/1806.08514](http://arxiv.org/pdf/1806.08514)

