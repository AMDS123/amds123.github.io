---
layout: post
title: "Joint Sub-bands Learning with Clique Structures for Wavelet Domain Super-Resolution"
date: 2018-09-12 15:19:37
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Quantitative
author: Zhisheng Zhong, Tiancheng Shen, Yibo Yang, Zhouchen Lin, Chao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have recently achieved great success in single-image super-resolution (SISR). However, these methods tend to produce over-smoothed outputs and miss some textural details. To solve these problems, we propose the Super-Resolution CliqueNet (SRCliqueNet) to reconstruct the high resolution (HR) image with better textural details in the wavelet domain. The proposed SRCliqueNet firstly extracts a set of feature maps from the low resolution (LR) image by the clique blocks group. Then we send the set of feature maps to the clique up-sampling module to reconstruct the HR image. The clique up-sampling module consists of four sub-nets which predict the high resolution wavelet coefficients of four sub-bands. Since we consider the edge feature properties of four sub-bands, the four sub-nets are connected to the others so that they can learn the coefficients of four sub-bands jointly. Finally we apply inverse discrete wavelet transform (IDWT) to the output of four sub-nets at the end of the clique up-sampling module to increase the resolution and reconstruct the HR image. Extensive quantitative and qualitative experiments on benchmark datasets show that our method achieves superior performance over the state-of-the-art methods.

##### Abstract (translated by Google)
卷积神经网络（CNN）最近在单图像超分辨率（SISR）中取得了巨大成功。但是，这些方法往往会产生过度平滑的输出并错过一些纹理细节。为了解决这些问题，我们提出了超分辨率CliqueNet（SRCliqueNet）来重建高分辨率（HR）图像，在小波域中具有更好的纹理细节。所提出的SRCliqueNet首先通过clique块组从低分辨率（LR）图像中提取一组特征图。然后我们将这组特征映射发送到clique up-sampling模块以重建HR图像。集团上采样模块由四个子网组成，用于预测四个子带的高分辨率小波系数。由于我们考虑了四个子带的边缘特征属性，因此四个子网连接到其他子网，以便它们可以共同学习四个子带的系数。最后，我们将逆离散小波变换（IDWT）应用于集团上采样模块末端的四个子网的输出，以提高分辨率并重建HR图像。对基准数据集进行广泛的定量和定性实验表明，我们的方法比最先进的方法具有更好的性能。

##### URL
[http://arxiv.org/abs/1809.04508](http://arxiv.org/abs/1809.04508)

##### PDF
[http://arxiv.org/pdf/1809.04508](http://arxiv.org/pdf/1809.04508)

