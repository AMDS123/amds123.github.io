---
layout: post
title: "Light Field Denoising via Anisotropic Parallax Analysis in a CNN Framework"
date: 2018-05-31 07:41:37
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jie Chen, Junhui Hou, Lap-Pui Chau
mathjax: true
---

* content
{:toc}

##### Abstract
Light field (LF) cameras provide perspective information of scenes by taking directional measurements of the focusing light rays. The raw outputs are usually dark with additive camera noise, which impedes subsequent processing and applications. We propose a novel LF denoising framework based on anisotropic parallax analysis (APA). Two convolutional neural networks are jointly designed for the task: first, the structural parallax synthesis network predicts the parallax details for the entire LF based on a set of anisotropic parallax features. These novel features can efficiently capture the high frequency perspective components of a LF from noisy observations. Second, the view-dependent detail compensation network restores non-Lambertian variation to each LF view by involving view-specific spatial energies. Extensive experiments show that the proposed APA LF denoiser provides a much better denoising performance than state-of-the-art methods in terms of visual quality and in preservation of parallax details.

##### Abstract (translated by Google)
光场（LF）相机通过对聚焦光线进行定向测量来提供场景的透视信息。原始输出通常是黑暗的，具有附加的相机噪声，这妨碍了后续的处理和应用。我们提出了一种基于各向异性视差分析（APA）的新型LF降噪框架。两个卷积神经网络共同设计用于该任务：首先，结构视差合成网络基于一组各向异性视差特征来预测整个LF的视差细节。这些新颖的功能可以从噪声观测中有效捕获LF的高频透视分量。其次，依赖视点的细节补偿网络通过涉及视点特定的空间能量来恢复每个LF视图的非朗伯变化。大量实验表明，所提出的APA LF降噪器在视觉质量和视差细节保存方面比最先进的方法提供了更好的降噪性能。

##### URL
[http://arxiv.org/abs/1805.12358](http://arxiv.org/abs/1805.12358)

##### PDF
[http://arxiv.org/pdf/1805.12358](http://arxiv.org/pdf/1805.12358)

