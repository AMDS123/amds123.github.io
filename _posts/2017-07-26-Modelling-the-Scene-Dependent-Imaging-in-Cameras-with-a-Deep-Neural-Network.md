---
layout: post
title: "Modelling the Scene Dependent Imaging in Cameras with a Deep Neural Network"
date: 2017-07-26 10:04:23
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Seonghyeon Nam, Seon Joo Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel deep learning framework that models the scene dependent image processing inside cameras. Often called as the radiometric calibration, the process of recovering RAW images from processed images (JPEG format in the sRGB color space) is essential for many computer vision tasks that rely on physically accurate radiance values. All previous works rely on the deterministic imaging model where the color transformation stays the same regardless of the scene and thus they can only be applied for images taken under the manual mode. In this paper, we propose a data-driven approach to learn the scene dependent and locally varying image processing inside cameras under the automode. Our method incorporates both the global and the local scene context into pixel-wise features via multi-scale pyramid of learnable histogram layers. The results show that we can model the imaging pipeline of different cameras that operate under the automode accurately in both directions (from RAW to sRGB, from sRGB to RAW) and we show how we can apply our method to improve the performance of image deblurring.

##### Abstract (translated by Google)
我们提出了一个新的深度学习框架，模拟相机内的场景依赖图像处理。通常被称为辐射定标，从经过处理的图像（sRGB色彩空间中的JPEG格式）中恢复RAW图像的过程，对于许多依靠物理上精确的辐射值的计算机视觉任务而言至关重要。所有以前的作品依赖于确定性成像模型，其中颜色变换保持相同而不管场景如何，因此它们只能用于在手动模式下拍摄的图像。在本文中，我们提出了一个数据驱动的方法来学习场景相关和局部变化的图像处理在相机下的自动机器。我们的方法通过可学习直方图层的多尺度金字塔将全局和局部场景上下文结合到像素方式的特征中。结果表明，我们可以在两个方向（从RAW到sRGB，从sRGB到RAW）准确地模拟在自动模式下运行的不同相机的成像管道，并展示如何应用我们的方法来提高图像去模糊的性能。

##### URL
[https://arxiv.org/abs/1707.08350](https://arxiv.org/abs/1707.08350)

##### PDF
[https://arxiv.org/pdf/1707.08350](https://arxiv.org/pdf/1707.08350)

