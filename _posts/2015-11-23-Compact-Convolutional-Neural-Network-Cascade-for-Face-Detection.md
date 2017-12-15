---
layout: post
title: "Compact Convolutional Neural Network Cascade for Face Detection"
date: 2015-11-23 20:01:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Ilya Kalinovskii, Vladimir Spitsyn
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of faces detection in images or video streams is a classical problem of computer vision. The multiple solutions of this problem have been proposed, but the question of their optimality is still open. Many algorithms achieve a high quality face detection, but at the cost of high computational complexity. This restricts their application in the real-time systems. This paper presents a new solution of the frontal face detection problem based on compact convolutional neural networks cascade. The test results on FDDB dataset show that it is competitive with state-of-the-art algorithms. This proposed detector is implemented using three technologies: SSE/AVX/AVX2 instruction sets for Intel CPUs, Nvidia CUDA, OpenCL. The detection speed of our approach considerably exceeds all the existing CPU-based and GPU-based algorithms. Because of high computational efficiency, our detector can processing 4K Ultra HD video stream in real time (up to 27 fps) on mobile platforms (Intel Ivy Bridge CPUs and Nvidia Kepler GPUs) in searching objects with the dimension 60x60 pixels or higher. At the same time its performance weakly dependent on the background and number of objects in scene. This is achieved by the asynchronous computation of stages in the cascade.

##### Abstract (translated by Google)
图像或视频流中的人脸检测问题是计算机视觉的经典问题。这个问题的多重解决方法已经被提出，但是它们的最优性问题仍然是开放的。许多算法实现高质量的人脸检测，但代价是计算复杂度高。这限制了它们在实时系统中的应用。本文提出了一种基于紧致卷积神经网络级联的正面人脸检测新方法。 FDDB数据集的测试结果表明，它与最先进的算法相竞争。这个建议的检测器使用三种技术实现：用于Intel CPU的SSE / AVX / AVX2指令集，Nvidia CUDA，OpenCL。我们的方法的检测速度大大超过了所有现有的基于CPU和GPU的算法。由于计算效率高，我们的探测器可以在移动平台（Intel Ivy Bridge CPU和Nvidia Kepler GPU）上实时处理4K超高清视频流（最高27 fps），以搜索尺寸为60x60像素或更高的物体。同时它的表现依赖于场景中的背景和数量。这是通过级联中的阶段的异步计算来实现的。

##### URL
[https://arxiv.org/abs/1508.01292](https://arxiv.org/abs/1508.01292)

##### PDF
[https://arxiv.org/pdf/1508.01292](https://arxiv.org/pdf/1508.01292)

