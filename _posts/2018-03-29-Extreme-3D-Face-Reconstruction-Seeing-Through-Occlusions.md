---
layout: post
title: "Extreme 3D Face Reconstruction: Seeing Through Occlusions"
date: 2018-03-29 23:22:21
categories: arXiv_CV
tags: arXiv_CV Face CNN Quantitative
author: Anh Tuan Tran, Tal Hassner, Iacopo Masi, Eran Paz, Yuval Nirkin, Gerard Medioni
mathjax: true
---

* content
{:toc}

##### Abstract
Existing single view, 3D face reconstruction methods can produce beautifully detailed 3D results, but typically only for near frontal, unobstructed viewpoints. We describe a system designed to provide detailed 3D reconstructions of faces viewed under extreme conditions, out of plane rotations, and occlusions. Motivated by the concept of bump mapping, we propose a layered approach which decouples estimation of a global shape from its mid-level details (e.g., wrinkles). We estimate a coarse 3D face shape which acts as a foundation and then separately layer this foundation with details represented by a bump map. We show how a deep convolutional encoder-decoder can be used to estimate such bump maps. We further show how this approach naturally extends to generate plausible details for occluded facial regions. We test our approach and its components extensively, quantitatively demonstrating the invariance of our estimated facial details. We further provide numerous qualitative examples showing that our method produces detailed 3D face shapes in viewing conditions where existing state of the art often break down.

##### Abstract (translated by Google)
现有的单一视图，3D人脸重建方法可以生成精美的3D结果，但通常仅适用于近前方，通畅的视点。我们描述了一个系统，旨在提供在极端条件下，在平面外旋转和遮挡下观看的脸部的详细3D重建。受到凹凸贴图概念的启发，我们提出了一种分层方法，将全局形状的估计与其中间层细节（例如皱纹）分离开来。我们估计一个粗糙的3D人脸形状作为基础，然后分别将这个基础与由凹凸贴图表示的细节分开。我们展示了如何使用深度卷积编码器 - 解码器来估计这种凹凸贴图。我们进一步展示了这种方法如何自然延伸以生成遮挡面部区域的可信细节。我们广泛测试我们的方法及其组件，定量展示我们估计的面部细节的不变性。我们进一步提供了大量的定性实例，表明我们的方法在现有技术状态经常发生故障的观察条件下生成详细的3D面部形状。

##### URL
[http://arxiv.org/abs/1712.05083](http://arxiv.org/abs/1712.05083)

##### PDF
[http://arxiv.org/pdf/1712.05083](http://arxiv.org/pdf/1712.05083)

