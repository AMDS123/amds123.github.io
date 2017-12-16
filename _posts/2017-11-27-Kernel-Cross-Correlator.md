---
layout: post
title: "Kernel Cross-Correlator"
date: 2017-11-27 07:28:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection Relation Recognition
author: Chen Wang, Le Zhang, Lihua Xie, Junsong Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-correlator plays a significant role in many visual perception tasks, such as object detection and tracking. Beyond the linear cross-correlator, this paper proposes a kernel cross-correlator (KCC) that breaks traditional limitations. First, by introducing the kernel trick, the KCC extends the linear cross-correlation to non-linear space, which is more robust to signal noises and distortions. Second, the connection to the existing works shows that KCC provides a unified solution for correlation filters. Third, KCC is applicable to any kernel function and is not limited to circulant structure on training data, thus it is able to predict affine transformations with customized properties. Last, by leveraging the fast Fourier transform (FFT), KCC eliminates direct calculation of kernel vectors, thus achieves better performance yet still with a reasonable computational cost. Comprehensive experiments on visual tracking and human activity recognition using wearable devices demonstrate its robustness, flexibility, and efficiency. The source codes of both experiments are released at this https URL

##### Abstract (translated by Google)
互相关器在许多视觉感知任务中起着重要的作用，例如对象检测和跟踪。除了线性交叉相关器之外，本文提出了一个突破传统限制的内核交叉相关器（KCC）。首先，通过引入内核技巧，KCC将线性互相关延伸到非线性空间，这对于信号噪声和失真更加鲁棒。其次，与现有作品的联系表明，KCC为相关滤波器提供了统一的解决方案。第三，KCC适用于任何核函数，不限于训练数据的循环结构，因此可以预测具有定制属性的仿射变换。最后，通过利用快速傅里叶变换（FFT），KCC消除了对核矢量的直接计算，从而获得了更好的性能，但仍然具有合理的计算成本。使用可穿戴设备进行视觉跟踪和人类活动识别的全面实验证明了其可靠性，灵活性和效率。这两个实验的源代码都在这个https URL上发布

##### URL
[https://arxiv.org/abs/1709.05936](https://arxiv.org/abs/1709.05936)

##### PDF
[https://arxiv.org/pdf/1709.05936](https://arxiv.org/pdf/1709.05936)

