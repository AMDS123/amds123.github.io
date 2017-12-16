---
layout: post
title: "Deep Bilateral Learning for Real-Time Image Enhancement"
date: 2017-08-22 19:26:08
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement CNN
author: Michaël Gharbi, Jiawen Chen, Jonathan T. Barron, Samuel W. Hasinoff, Frédo Durand
mathjax: true
---

* content
{:toc}

##### Abstract
Performance is a critical challenge in mobile image processing. Given a reference imaging pipeline, or even human-adjusted pairs of images, we seek to reproduce the enhancements and enable real-time evaluation. For this, we introduce a new neural network architecture inspired by bilateral grid processing and local affine color transforms. Using pairs of input/output images, we train a convolutional neural network to predict the coefficients of a locally-affine model in bilateral space. Our architecture learns to make local, global, and content-dependent decisions to approximate the desired image transformation. At runtime, the neural network consumes a low-resolution version of the input image, produces a set of affine transformations in bilateral space, upsamples those transformations in an edge-preserving fashion using a new slicing node, and then applies those upsampled transformations to the full-resolution image. Our algorithm processes high-resolution images on a smartphone in milliseconds, provides a real-time viewfinder at 1080p resolution, and matches the quality of state-of-the-art approximation techniques on a large class of image operators. Unlike previous work, our model is trained off-line from data and therefore does not require access to the original operator at runtime. This allows our model to learn complex, scene-dependent transformations for which no reference implementation is available, such as the photographic edits of a human retoucher.

##### Abstract (translated by Google)
性能是移动图像处理中的关键挑战。给定一个参考成像管道，甚至是人工调整的图像对，我们试图重现增强功能，并实现实时评估。为此，我们引入一个受双边网格处理和局部仿射变换启发的新型神经网络体系结构。使用输入/输出图像对，我们训练一个卷积神经网络来预测双边空间中局部仿射模型的系数。我们的架构学习使局部，全局和依赖内容的决策接近所需的图像转换。在运行时，神经网络消耗输入图像的低分辨率版本，在双边空间中产生一组仿射变换，使用新的分割节点以保持边缘的方式对这些变换进行上采样，然后将这些经上采样的变换应用于全分辨率的图像。我们的算法在毫秒级的智能手机上处理高分辨率图像，提供1080p分辨率的实时取景器，并匹配大量图像操作员的最新近似技术的质量。与以前的工作不同，我们的模型是从数据中脱机培训的，因此不需要在运行时访问原始的操作员。这使得我们的模型能够学习复杂的，依赖于场景的转换，没有任何参考实现可用，比如人类润饰的照片编辑。

##### URL
[https://arxiv.org/abs/1707.02880](https://arxiv.org/abs/1707.02880)

##### PDF
[https://arxiv.org/pdf/1707.02880](https://arxiv.org/pdf/1707.02880)

