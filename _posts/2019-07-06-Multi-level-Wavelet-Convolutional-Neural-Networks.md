---
layout: post
title: "Multi-level Wavelet Convolutional Neural Networks"
date: 2019-07-06 14:19:03
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse CNN Classification
author: Pengju Liu, Hongzhi Zhang, Wei Lian, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
In computer vision, convolutional networks (CNNs) often adopts pooling to enlarge receptive field which has the advantage of low computational complexity. However, pooling can cause information loss and thus is detrimental to further operations such as features extraction and analysis. Recently, dilated filter has been proposed to trade off between receptive field size and efficiency. But the accompanying gridding effect can cause a sparse sampling of input images with checkerboard patterns. To address this problem, in this paper, we propose a novel multi-level wavelet CNN (MWCNN) model to achieve better trade-off between receptive field size and computational efficiency. The core idea is to embed wavelet transform into CNN architecture to reduce the resolution of feature maps while at the same time, increasing receptive field. Specifically, MWCNN for image restoration is based on U-Net architecture, and inverse wavelet transform (IWT) is deployed to reconstruct the high resolution (HR) feature maps. The proposed MWCNN can also be viewed as an improvement of dilated filter and a generalization of average pooling, and can be applied to not only image restoration tasks, but also any CNNs requiring a pooling operation. The experimental results demonstrate effectiveness of the proposed MWCNN for tasks such as image denoising, single image super-resolution, JPEG image artifacts removal and object classification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03128](http://arxiv.org/abs/1907.03128)

##### PDF
[http://arxiv.org/pdf/1907.03128](http://arxiv.org/pdf/1907.03128)

