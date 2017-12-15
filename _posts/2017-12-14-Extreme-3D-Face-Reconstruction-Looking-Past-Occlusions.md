---
layout: post
title: "Extreme 3D Face Reconstruction: Looking Past Occlusions"
date: 2017-12-14 03:53:52
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
现有的单视图，三维人脸重建方法可以产生精美的详细的三维结果，但通常只用于近前方，通畅的视点。我们描述了一个系统，旨在提供在极端条件下，在平面外旋转和遮挡下观看的脸部的详细3D重建。受到凹凸贴图概念的启发，我们提出了一种分层的方法，将全局形状的估计与其中间层次的细节（例如皱纹）分离开来。我们估计一个粗糙的三维脸部形状作为一个基础，然后单独分层这个基础与凹凸贴图代表的细节。我们展示了如何使用深度卷积编码器 - 解码器来估计这种凹凸贴图。我们进一步展示了这种方法如何自然延伸，为闭合的面部区域生成合理的细节。我们广泛测试我们的方法及其组件，定量展示我们估计的面部细节的不变性。我们进一步提供了大量的定性实例，显示我们的方法在现有技术状态经常破裂的观察条件下产生详细的3D面部形状。

##### URL
[http://arxiv.org/abs/1712.05083](http://arxiv.org/abs/1712.05083)

##### PDF
[http://arxiv.org/pdf/1712.05083](http://arxiv.org/pdf/1712.05083)

