---
layout: post
title: "Accurate Spectral Super-resolution from Single RGB Image Using Multi-scale CNN"
date: 2018-06-10 02:32:02
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yiqi Yan, Lei Zhang, Wei Wei, Yanning Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Different from traditional hyperspectral super-resolution approaches that focus on improving the spatial resolution, spectral super-resolution aims at producing a high-resolution hyperspectral image from the RGB observation with super-resolution in spectral domain. However, it is challenging to accurately reconstruct a high-dimensional continuous spectrum from three discrete intensity values at each pixel, since too much information is lost during the procedure where the latent hyperspectral image is downsampled (e.g., with x10 scaling factor) in spectral domain to produce an RGB observation. To address this problem, we present a multi-scale deep convolutional neural network (CNN) to explicitly map the input RGB image into a hyperspectral image. Through symmetrically downsampling and upsampling the intermediate feature maps in a cascading paradigm, the local and non-local image information can be jointly encoded for spectral representation, ultimately improving the spectral reconstruction accuracy. Extensive experiments on a large hyperspectral dataset demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)
与专注于提高空间分辨率的传统超光谱超分辨率方法不同，光谱超分辨率的目标是从RGB观测到的超分辨率光谱域中生成高分辨率高光谱图像。然而，从每个像素处的三个离散强度值准确地重建高维连续光谱是具​​有挑战性的，因为在潜在高光谱图像在频谱域中下采样（例如，具有x10缩放因子）的过程期间丢失了太多信息以产生RGB观察。为了解决这个问题，我们提出了一个多尺度的深度卷积神经网络（CNN）来将输入的RGB图像明确地映射成高光谱图像。通过在级联范例中对称下采样和上采样中间特征地图，可以对局部和非局部图像信息进行联合编码以用于谱表示，最终改善谱重构精度。在大型高光谱数据集上的大量实验证明了所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1806.03575](http://arxiv.org/abs/1806.03575)

##### PDF
[http://arxiv.org/pdf/1806.03575](http://arxiv.org/pdf/1806.03575)

