---
layout: post
title: "Color Constancy by Learning to Predict Chromaticity from Luminance"
date: 2015-12-07 18:49:15
categories: arXiv_CV
tags: arXiv_CV Face Inference Gradient_Descent
author: Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
Color constancy is the recovery of true surface color from observed color, and requires estimating the chromaticity of scene illumination to correct for the bias it induces. In this paper, we show that the per-pixel color statistics of natural scenes---without any spatial or semantic context---can by themselves be a powerful cue for color constancy. Specifically, we describe an illuminant estimation method that is built around a "classifier" for identifying the true chromaticity of a pixel given its luminance (absolute brightness across color channels). During inference, each pixel's observed color restricts its true chromaticity to those values that can be explained by one of a candidate set of illuminants, and applying the classifier over these values yields a distribution over the corresponding illuminants. A global estimate for the scene illuminant is computed through a simple aggregation of these distributions across all pixels. We begin by simply defining the luminance-to-chromaticity classifier by computing empirical histograms over discretized chromaticity and luminance values from a training set of natural images. These histograms reflect a preference for hues corresponding to smooth reflectance functions, and for achromatic colors in brighter pixels. Despite its simplicity, the resulting estimation algorithm outperforms current state-of-the-art color constancy methods. Next, we propose a method to learn the luminance-to-chromaticity classifier "end-to-end". Using stochastic gradient descent, we set chromaticity-luminance likelihoods to minimize errors in the final scene illuminant estimates on a training set. This leads to further improvements in accuracy, most significantly in the tail of the error distribution.

##### Abstract (translated by Google)
颜色恒定性是从观察到的颜色恢复真实的表面颜色，并且需要估计场景照明的色度以校正其引起的偏差。在本文中，我们表明，自然场景的每像素颜色统计 - 没有任何空间或语义上下文 - 自己可以是一个强大的颜色恒常的提示。具体来说，我们描述了一个光源估计方法，它是围绕“分类器”建立的，用于在给定亮度（彩色通道上的绝对亮度）的情况下识别像素的真实色度。在推断过程中，每个像素观察到的颜色将其真正的色度限制为那些可以由候选光源集合中的一个来解释的值，并且将分类器应用于这些值将产生对相应光源的分布。通过对所有像素的这些分布的简单聚合来计算场景光源的全局估计。我们首先简单地定义亮度色度分类器，通过计算自然图像训练集的离散化色度和亮度值的经验直方图。这些直方图反映了与平滑反射函数相对应的色调偏好，以及更亮像素中的消色差颜色。尽管其简单性，所得到的估计算法优于当前最先进的颜色恒定性方法。接下来，我们提出了一种学习亮度到色度分类器“端到端”的方法。使用随机梯度下降，我们设置色度 - 亮度可能性以最小化训练集上最终场景光源估计中的误差。这导致精度的进一步提高，最重要的是在错误分布的尾部。

##### URL
[https://arxiv.org/abs/1506.02167](https://arxiv.org/abs/1506.02167)

##### PDF
[https://arxiv.org/pdf/1506.02167](https://arxiv.org/pdf/1506.02167)

