---
layout: post
title: "Lose The Views: Limited Angle CT Reconstruction via Implicit Sinogram Completion"
date: 2017-11-28 16:37:14
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Rushil Anirudh, Hyojin Kim, Jayaraman J. Thiagarajan, K. Aditya Mohan, Kyle Champley, Timo Bremer
mathjax: true
---

* content
{:toc}

##### Abstract
Computed Tomography (CT) reconstruction is a fundamental component to a wide variety of applications ranging from security, to healthcare. The classical techniques require measuring projections, called sinograms, from a full 180$^\circ$ view of the object. This is impractical in a limited angle scenario, when the viewing angle is less than 180$^\circ$, which can occur due to different factors including restrictions on scanning time, limited flexibility of scanner rotation, etc. The sinograms obtained as a result, cause existing techniques to produce highly artifact-laden reconstructions. In this paper, we propose to address this problem through implicit sinogram completion, on a challenging real world dataset containing scans of common checked-in luggage. We propose a system, consisting of 1D and 2D convolutional neural networks, that operates on a limited angle sinogram to directly produce the best estimate of a reconstruction. Next, we use the x-ray transform on this reconstruction to obtain a "completed" sinogram, as if it came from a full 180$^\circ$ measurement. We feed this to standard analytical and iterative reconstruction techniques to obtain the final reconstruction. We show with extensive experimentation that this combined strategy outperforms many competitive baselines. We also propose a measure of confidence for the reconstruction that enables a practitioner to gauge the reliability of a prediction made by our network. We show that this measure is a strong indicator of quality as measured by the PSNR, while not requiring ground truth at test time. Finally, using a segmentation experiment, we show that our reconstruction preserves the 3D structure of objects effectively.

##### Abstract (translated by Google)
计算机断层扫描（CT）重建是从安全到医疗保健等广泛应用的基本组成部分。经典的技术需要测量投影，称为正弦图，从对象的整个180度视角来看。当视角小于180°时，这是不切实际的，这可能是由于不同的因素，包括对扫描时间的限制，扫描器旋转的有限灵活性等等而产生的。作为结果获得的正弦图，导致现有的技术产生高度神器重建。在本文中，我们建议通过隐式正弦图完成来解决这个问题，在包含普通托运行李的扫描的具有挑战性的现实世界数据集上。我们提出了一个由一维和二维卷积神经网络组成的系统，它在有限角度的正弦图上运行，直接产生重建的最佳估计。接下来，我们在这个重建上使用X射线变换来获得“完成”的正弦图，就好像它来自完整的180度测量。我们把这个喂给标准的分析和迭代重建技术来获得最终的重建。我们用广泛的实验表明，这种组合策略胜过了很多竞争基线。我们还提出了一个重建的信心的措施，使从业者能够衡量我们的网络预测的可靠性。我们表明，这个衡量标准是衡量PSNR质量的有力指标，而在测试时不需要事实真相。最后，利用分割实验，证明了我们的重构有效地保留了对象的三维结构。

##### URL
[https://arxiv.org/abs/1711.10388](https://arxiv.org/abs/1711.10388)

##### PDF
[https://arxiv.org/pdf/1711.10388](https://arxiv.org/pdf/1711.10388)

