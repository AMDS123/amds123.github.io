---
layout: post
title: "Efficient Multi-Frequency Phase Unwrapping using Kernel Density Estimation"
date: 2016-08-18 08:49:13
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Felix Järemo Lawin, Per-Erik Forssén, Hannes Ovrén
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce an efficient method to unwrap multi-frequency phase estimates for time-of-flight ranging. The algorithm generates multiple depth hypotheses and uses a spatial kernel density estimate (KDE) to rank them. The confidence produced by the KDE is also an effective means to detect outliers. We also introduce a new closed-form expression for phase noise prediction, that better fits real data. The method is applied to depth decoding for the Kinect v2 sensor, and compared to the Microsoft Kinect SDK and to the open source driver libfreenect2. The intended Kinect v2 use case is scenes with less than 8m range, and for such cases we observe consistent improvements, while maintaining real-time performance. When extending the depth range to the maximal value of 8.75m, we get about 52% more valid measurements than libfreenect2. The effect is that the sensor can now be used in large depth scenes, where it was previously not a good choice. Code and supplementary material are available at this http URL

##### Abstract (translated by Google)
在本文中，我们介绍一种有效的方法来展开飞行时间测距的多频率相位估计。该算法生成多个深度假设，并使用空间核密度估计（KDE）对它们进行排序。 KDE产生的信心也是检测异常值的有效手段。我们还引入了一个新的闭式表达式用于相位噪声预测，更适合实际的数据。该方法适用于Kinect v2传感器的深度解码，并与Microsoft Kinect SDK和开源驱动libfreenect2进行比较。预期的Kinect v2使用案例是小于8米范围的场景，在这种情况下，我们观察到一致的改进，同时保持实时性能。当将深度范围扩展到最大值8.75m时，我们比libfreenect2获得了大约52％的有效测量结果。其效果是，传感器现在可以用于深度较大的场景，以前不是一个好的选择。代码和补充材料可在此http URL中找到

##### URL
[https://arxiv.org/abs/1608.05209](https://arxiv.org/abs/1608.05209)

##### PDF
[https://arxiv.org/pdf/1608.05209](https://arxiv.org/pdf/1608.05209)

