---
layout: post
title: "Deep Laplacian Pyramid Networks for Fast and Accurate Super-Resolution"
date: 2017-10-09 22:47:12
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Prediction Quantitative
author: Wei-Sheng Lai, Jia-Bin Huang, Narendra Ahuja, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have recently demonstrated high-quality reconstruction for single-image super-resolution. In this paper, we propose the Laplacian Pyramid Super-Resolution Network (LapSRN) to progressively reconstruct the sub-band residuals of high-resolution images. At each pyramid level, our model takes coarse-resolution feature maps as input, predicts the high-frequency residuals, and uses transposed convolutions for upsampling to the finer level. Our method does not require the bicubic interpolation as the pre-processing step and thus dramatically reduces the computational complexity. We train the proposed LapSRN with deep supervision using a robust Charbonnier loss function and achieve high-quality reconstruction. Furthermore, our network generates multi-scale predictions in one feed-forward pass through the progressive reconstruction, thereby facilitates resource-aware applications. Extensive quantitative and qualitative evaluations on benchmark datasets show that the proposed algorithm performs favorably against the state-of-the-art methods in terms of speed and accuracy.

##### Abstract (translated by Google)
卷积神经网络最近展示了高质量的单幅图像超分辨率重建。在本文中，我们提出拉普拉斯金字塔超分辨率网络（LapSRN）逐步重建高分辨率图像的子带残差。在每个金字塔层面，我们的模型将粗分辨率的特征地图作为输入，预测高频残差，并使用转置卷积进行上采样到更精细的水平。我们的方法不需要双三次插值作为预处理步骤，因此大大降低了计算复杂度。我们使用强大的Charbonnier损失函数对深层监督的LapSRN进行训练，并实现高质量的重建。此外，我们的网络通过渐进式重构在前馈中产生多尺度预测，从而有助于资源感知应用。对基准数据集进行广泛的定量和定性评估表明，所提出的算法在速度和准确性方面优于现有技术的方法。

##### URL
[https://arxiv.org/abs/1704.03915](https://arxiv.org/abs/1704.03915)

##### PDF
[https://arxiv.org/pdf/1704.03915](https://arxiv.org/pdf/1704.03915)

