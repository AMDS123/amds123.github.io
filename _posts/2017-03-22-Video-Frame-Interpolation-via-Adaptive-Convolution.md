---
layout: post
title: "Video Frame Interpolation via Adaptive Convolution"
date: 2017-03-22 04:31:38
categories: arXiv_CV
tags: arXiv_CV CNN
author: Simon Niklaus, Long Mai, Feng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Video frame interpolation typically involves two steps: motion estimation and pixel synthesis. Such a two-step approach heavily depends on the quality of motion estimation. This paper presents a robust video frame interpolation method that combines these two steps into a single process. Specifically, our method considers pixel synthesis for the interpolated frame as local convolution over two input frames. The convolution kernel captures both the local motion between the input frames and the coefficients for pixel synthesis. Our method employs a deep fully convolutional neural network to estimate a spatially-adaptive convolution kernel for each pixel. This deep neural network can be directly trained end to end using widely available video data without any difficult-to-obtain ground-truth data like optical flow. Our experiments show that the formulation of video interpolation as a single convolution process allows our method to gracefully handle challenges like occlusion, blur, and abrupt brightness change and enables high-quality video frame interpolation.

##### Abstract (translated by Google)
视频帧插值通常涉及两个步骤：运动估计和像素合成。这种两步法很大程度上取决于运动估计的质量。本文提出了一个健壮的视频帧插值方法，将这两个步骤组合成一个单一的过程。具体来说，我们的方法考虑插值帧的像素合成作为两个输入帧的本地卷积。卷积核捕获输入帧之间的局部运动和像素合成的系数。我们的方法采用深度完全卷积神经网络来估计每个像素的空间自适应卷积核。这个深度神经网络可以直接使用广泛可用的视频数据来端对端训练，而不需要任何难以获得的地面真实数据，如光流。我们的实验表明，将视频插值作为一个单一的卷积过程，使得我们的方法能够优雅地处理诸如遮挡，模糊和突然的亮度变化等挑战，并实现高质量的视频帧插值。

##### URL
[https://arxiv.org/abs/1703.07514](https://arxiv.org/abs/1703.07514)

##### PDF
[https://arxiv.org/pdf/1703.07514](https://arxiv.org/pdf/1703.07514)

