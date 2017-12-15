---
layout: post
title: "Recursive Training of 2D-3D Convolutional Networks for Neuronal Boundary Detection"
date: 2015-08-20 00:46:38
categories: arXiv_CV
tags: arXiv_CV CNN Detection Recognition
author: Kisuk Lee, Aleksandar Zlateski, Ashwin Vishwanathan, H. Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
Efforts to automate the reconstruction of neural circuits from 3D electron microscopic (EM) brain images are critical for the field of connectomics. An important computation for reconstruction is the detection of neuronal boundaries. Images acquired by serial section EM, a leading 3D EM technique, are highly anisotropic, with inferior quality along the third dimension. For such images, the 2D max-pooling convolutional network has set the standard for performance at boundary detection. Here we achieve a substantial gain in accuracy through three innovations. Following the trend towards deeper networks for object recognition, we use a much deeper network than previously employed for boundary detection. Second, we incorporate 3D as well as 2D filters, to enable computations that use 3D context. Finally, we adopt a recursively trained architecture in which a first network generates a preliminary boundary map that is provided as input along with the original image to a second network that generates a final boundary map. Backpropagation training is accelerated by ZNN, a new implementation of 3D convolutional networks that uses multicore CPU parallelism for speed. Our hybrid 2D-3D architecture could be more generally applicable to other types of anisotropic 3D images, including video, and our recursive framework for any image labeling problem.

##### Abstract (translated by Google)
从3D电子显微镜（EM）脑图像自动化重建神经回路的努力对于连接组学领域是至关重要的。一个重要的重建计算是神经元边界的检测。通过连续截面EM获得的图像是领先的3D EM技术，具有高度的各向异性，沿着第三维质量较差。对于这样的图像，2D最大共享卷积网络已经为边界检测设置了性能标准。在这里，我们通过三项创新实现了准确的收益。随着对象识别网络的深入发展，我们使用比以前用于边界检测更深的网络。其次，我们将3D和2D滤镜结合起来，以支持使用3D上下文的计算。最后，我们采用递归训练的架构，其中第一个网络生成初步的边界图，该边界图随原始图像一起作为输入提供给产生最终边界图的第二网络。 ZNN加速了反向传播培训，ZNN是一种使用多核CPU并行性来提高速度的3D卷积网络的新实现。我们的混合2D-3D体系结构可能更普遍适用于其他类型的各向异性3D图像，包括视频，以及我们用于任何图像标记问题的递归框架。

##### URL
[https://arxiv.org/abs/1508.04843](https://arxiv.org/abs/1508.04843)

##### PDF
[https://arxiv.org/pdf/1508.04843](https://arxiv.org/pdf/1508.04843)

