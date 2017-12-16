---
layout: post
title: "Video Frame Interpolation via Adaptive Separable Convolution"
date: 2017-08-05 00:18:03
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Simon Niklaus, Long Mai, Feng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Standard video frame interpolation methods first estimate optical flow between input frames and then synthesize an intermediate frame guided by motion. Recent approaches merge these two steps into a single convolution process by convolving input frames with spatially adaptive kernels that account for motion and re-sampling simultaneously. These methods require large kernels to handle large motion, which limits the number of pixels whose kernels can be estimated at once due to the large memory demand. To address this problem, this paper formulates frame interpolation as local separable convolution over input frames using pairs of 1D kernels. Compared to regular 2D kernels, the 1D kernels require significantly fewer parameters to be estimated. Our method develops a deep fully convolutional neural network that takes two input frames and estimates pairs of 1D kernels for all pixels simultaneously. Since our method is able to estimate kernels and synthesizes the whole video frame at once, it allows for the incorporation of perceptual loss to train the neural network to produce visually pleasing frames. This deep neural network is trained end-to-end using widely available video data without any human annotation. Both qualitative and quantitative experiments show that our method provides a practical solution to high-quality video frame interpolation.

##### Abstract (translated by Google)
标准视频帧插值方法首先估计输入帧之间的光流，然后合成由运动引导的中间帧。最近的方法通过将输入帧与空间自适应内核进行卷积来将这两个步骤合并成单个卷积过程，所述空间自适应内核同时解释了运动和重采样。这些方法需要大的内核来处理大的运动，这限制了由于大内存需求而可以一次估计内核的像素的数量。为了解决这个问题，本文将帧插值作为使用一对一维内核的输入帧的局部可分卷积。与常规2D内核相比，1D内核需要的参数估计要少得多。我们的方法开发了一个深度完全卷积神经网络，它需要两个输入帧，并同时为所有像素估计一对一维内核。由于我们的方法能够估计内核并且一次合成整个视频帧，所以它允许并入感知损失来训练神经网络以产生视觉上令人愉快的帧。这个深度神经网络是使用广泛可用的视频数据进行端对端训练而不需要任何人类注释。定性和定量实验都表明，我们的方法为高质量的视频帧插值提供了一个实用的解决方案。

##### URL
[https://arxiv.org/abs/1708.01692](https://arxiv.org/abs/1708.01692)

##### PDF
[https://arxiv.org/pdf/1708.01692](https://arxiv.org/pdf/1708.01692)

