---
layout: post
title: "Reconfiguring the Imaging Pipeline for Computer Vision"
date: 2017-08-01 18:04:40
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Mark Buckler, Suren Jayasuriya, Adrian Sampson
mathjax: true
---

* content
{:toc}

##### Abstract
Advancements in deep learning have ignited an explosion of research on efficient hardware for embedded computer vision. Hardware vision acceleration, however, does not address the cost of capturing and processing the image data that feeds these algorithms. We examine the role of the image signal processing (ISP) pipeline in computer vision to identify opportunities to reduce computation and save energy. The key insight is that imaging pipelines should be designed to be configurable: to switch between a traditional photography mode and a low-power vision mode that produces lower-quality image data suitable only for computer vision. We use eight computer vision algorithms and a reversible pipeline simulation tool to study the imaging system's impact on vision performance. For both CNN-based and classical vision algorithms, we observe that only two ISP stages, demosaicing and gamma compression, are critical for task performance. We propose a new image sensor design that can compensate for skipping these stages. The sensor design features an adjustable resolution and tunable analog-to-digital converters (ADCs). Our proposed imaging system's vision mode disables the ISP entirely and configures the sensor to produce subsampled, lower-precision image data. This vision mode can save ~75% of the average energy of a baseline photography mode while having only a small impact on vision task accuracy.

##### Abstract (translated by Google)
深度学习的进步引发了嵌入式计算机视觉高效硬件研究的爆发。然而，硬件视觉加速并没有解决捕获和处理馈送这些算法的图像数据的成本。我们研究图像信号处理（ISP）管道在计算机视觉中的作用，以确定减少计算和节约能源的机会。关键的洞察力是成像管线应该设计成可配置的：在传统的摄影模式和低功率视觉模式之间切换，产生仅适用于计算机视觉的低质量图像数据。我们使用八种计算机视觉算法和一种可逆的流水线模拟工具来研究成像系统对视觉性能的影响。对于基于CNN和经典的视觉算法，我们观察到只有两个ISP阶段，去马赛克和伽玛压缩对于任务性能是至关重要的。我们提出了一种新的图像传感器设计，可以补偿跳过这些阶段。传感器设计具有可调节分辨率和可调模数转换器（ADC）。我们提出的成像系统的视觉模式完全禁用ISP，并将传感器配置为产生二次采样，较低精度的图像数据。这种视觉模式可以节省约75％的基线摄影模式的平均能量，同时对视觉任务的精确度只有很小的影响。

##### URL
[https://arxiv.org/abs/1705.04352](https://arxiv.org/abs/1705.04352)

##### PDF
[https://arxiv.org/pdf/1705.04352](https://arxiv.org/pdf/1705.04352)

