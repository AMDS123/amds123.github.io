---
layout: post
title: "Deep artifact learning for compressed sensing and parallel MRI"
date: 2017-03-03 12:02:32
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Dongwook Lee, Jaejun Yoo, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Compressed sensing MRI (CS-MRI) from single and parallel coils is one of the powerful ways to reduce the scan time of MR imaging with performance guarantee. However, the computational costs are usually expensive. This paper aims to propose a computationally fast and accurate deep learning algorithm for the reconstruction of MR images from highly down-sampled k-space data. Theory: Based on the topological analysis, we show that the data manifold of the aliasing artifact is easier to learn from a uniform subsampling pattern with additional low-frequency k-space data. Thus, we develop deep aliasing artifact learning networks for the magnitude and phase images to estimate and remove the aliasing artifacts from highly accelerated MR acquisition. Methods: The aliasing artifacts are directly estimated from the distorted magnitude and phase images reconstructed from subsampled k-space data so that we can get an aliasing-free images by subtracting the estimated aliasing artifact from corrupted inputs. Moreover, to deal with the globally distributed aliasing artifact, we develop a multi-scale deep neural network with a large receptive field. Results: The experimental results confirm that the proposed deep artifact learning network effectively estimates and removes the aliasing artifacts. Compared to existing CS methods from single and multi-coli data, the proposed network shows minimal errors by removing the coherent aliasing artifacts. Furthermore, the computational time is by order of magnitude faster. Conclusion: As the proposed deep artifact learning network immediately generates accurate reconstruction, it has great potential for clinical applications.

##### Abstract (translated by Google)
目的：单线圈和平行线圈的压缩传感MRI（CS-MRI）是降低MR成像扫描时间的有效方法之一，具有性能保证。但是，计算成本通常很昂贵。本文旨在提出一种计算快速而准确的深度学习算法，用于从高度下采样的k空间数据重建MR图像。理论：基于拓扑分析，我们证明了混叠伪像的数据流形更容易从具有附加的低频k空间数据的均匀子采样模式中学习。因此，我们开发了幅度和相位图像的深度混叠伪像学习网络，以估计和消除来自高度加速MR采集的混叠伪像。方法：从二次采样的k空间数据重建畸变的幅度和相位图像，直接估计混叠伪像，从而可以通过从损坏的输入中减去估计的混叠伪像来获得没有混叠的图像。此外，为了处理全局分布的锯齿伪影，我们开发了一个具有较大感受野的多尺度深度神经网络。结果：实验结果证实了所提出的深度人工学习网络有效估计和消除了混叠伪像。与单个和多个大肠杆菌数据的现有CS方法相比，所提出的网络通过去除相干混叠伪像而显示出最小的误差。而且，计算时间快了几个数量级。结论：由于提出的深层神器学习网络即刻产生准确的重建，具有很大的临床应用潜力。

##### URL
[https://arxiv.org/abs/1703.01120](https://arxiv.org/abs/1703.01120)

##### PDF
[https://arxiv.org/pdf/1703.01120](https://arxiv.org/pdf/1703.01120)

