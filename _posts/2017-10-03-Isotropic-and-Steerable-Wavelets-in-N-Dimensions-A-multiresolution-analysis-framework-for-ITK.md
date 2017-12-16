---
layout: post
title: "Isotropic and Steerable Wavelets in N Dimensions. A multiresolution analysis framework for ITK"
date: 2017-10-03 12:11:10
categories: arXiv_CV
tags: arXiv_CV Detection
author: Pablo Hernandez-Cerdan
mathjax: true
---

* content
{:toc}

##### Abstract
This document describes the implementation of the external module ITKIsotropicWavelets, a multiresolution (MRA) analysis framework using isotropic and steerable wavelets in the frequency domain. This framework provides the backbone for state of the art filters for denoising, feature detection or phase analysis in N-dimensions. It focus on reusability, and highly decoupled modules for easy extension and implementation of new filters, and it contains a filter for multiresolution phase analysis, The backbone of the multi-scale analysis is provided by an isotropic band-limited wavelet pyramid, and the detection of directional features is provided by coupling the pyramid with a generalized Riesz transform. The generalized Riesz transform of order N behaves like a smoothed version of the Nth order derivatives of the signal. Also, it is steerable: its components impulse responses can be rotated to any spatial orientation, reducing computation time when detecting directional features.

##### Abstract (translated by Google)
本文档介绍了外部模块ITKIsotropicWavelets的实现，这是一种在频域中使用各向同性和可控小波的多分辨率（MRA）分析框架。该框架为用于N维中的去噪，特征检测或相位分析的先进滤波器提供了骨干。它集中在可重用性和高度解耦的模块上，以便于扩展和实现新的滤波器，并且包含一个用于多分辨率相位分析的滤波器。多尺度分析的骨干由各向同性带限小波金字塔提供，的方向性特征是通过将金字塔与广义Riesz变换相结合来提供的。 N阶的广义Riesz变换就像信号的N阶导数的平滑版本。此外，它是可操纵的：它的分量脉冲响应可以旋转到任何空间方向，减少检测方向性时的计算时间。

##### URL
[https://arxiv.org/abs/1710.01103](https://arxiv.org/abs/1710.01103)

##### PDF
[https://arxiv.org/pdf/1710.01103](https://arxiv.org/pdf/1710.01103)

