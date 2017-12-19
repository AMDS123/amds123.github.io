---
layout: post
title: "A Picture is Worth a Billion Bits: Real-Time Image Reconstruction from Dense Binary Pixels"
date: 2015-12-05 10:13:16
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Tal Remez, Or Litany, Alex Bronstein
mathjax: true
---

* content
{:toc}

##### Abstract
The pursuit of smaller pixel sizes at ever increasing resolution in digital image sensors is mainly driven by the stringent price and form-factor requirements of sensors and optics in the cellular phone market. Recently, Eric Fossum proposed a novel concept of an image sensor with dense sub-diffraction limit one-bit pixels jots, which can be considered a digital emulation of silver halide photographic film. This idea has been recently embodied as the EPFL Gigavision camera. A major bottleneck in the design of such sensors is the image reconstruction process, producing a continuous high dynamic range image from oversampled binary measurements. The extreme quantization of the Poisson statistics is incompatible with the assumptions of most standard image processing and enhancement frameworks. The recently proposed maximum-likelihood (ML) approach addresses this difficulty, but suffers from image artifacts and has impractically high computational complexity. In this work, we study a variant of a sensor with binary threshold pixels and propose a reconstruction algorithm combining an ML data fitting term with a sparse synthesis prior. We also show an efficient hardware-friendly real-time approximation of this inverse operator.Promising results are shown on synthetic data as well as on HDR data emulated using multiple exposures of a regular CMOS sensor.

##### Abstract (translated by Google)
数字图像传感器在不断提高分辨率的情况下对更小像素尺寸的追求主要受到手机市场中传感器和光学器件严格的价格和外形要求的驱动。最近，Eric Fossum提出了一种具有致密的亚衍射极限的一位​​像素点的图像传感器的新概念，这可以被认为是卤化银照相胶片的数字仿真。这个想法最近被体现为EPFL Gigavision相机。这种传感器设计的主要瓶颈是图像重建过程，从过采样二进制测量产生连续的高动态范围图像。泊松统计量的极端量化不符合大多数标准图像处理和增强框架的假设。最近提出的最大似然（ML）方法解决了这个难题，但是存在图像伪像，并且具有不切实际的高计算复杂度。在这项工作中，我们研究了一个具有二值阈值像素的传感器的变体，并提出了一种ML数据拟合项与先前的稀疏合成相结合的重建算法。我们还展示了这种逆算子的高效的硬件友好的实时近似。合成数据以及使用常规CMOS传感器的多次曝光模拟的HDR数据显示了有益的结果。

##### URL
[https://arxiv.org/abs/1510.04601](https://arxiv.org/abs/1510.04601)

##### PDF
[https://arxiv.org/pdf/1510.04601](https://arxiv.org/pdf/1510.04601)

