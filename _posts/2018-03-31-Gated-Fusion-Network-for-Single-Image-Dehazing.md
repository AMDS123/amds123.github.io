---
layout: post
title: "Gated Fusion Network for Single Image Dehazing"
date: 2018-03-31 20:33:11
categories: arXiv_CV
tags: arXiv_CV
author: Wenqi Ren, Lin Ma, Jiawei Zhang, Jinshan Pan, Xiaochun Cao, Wei Liu, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an efficient algorithm to directly restore a clear image from a hazy input. The proposed algorithm hinges on an end-to-end trainable neural network that consists of an encoder and a decoder. The encoder is exploited to capture the context of the derived input images, while the decoder is employed to estimate the contribution of each input to the final dehazed result using the learned representations attributed to the encoder. The constructed network adopts a novel fusion-based strategy which derives three inputs from an original hazy image by applying White Balance (WB), Contrast Enhancing (CE), and Gamma Correction (GC). We compute pixel-wise confidence maps based on the appearance differences between these different inputs to blend the information of the derived inputs and preserve the regions with pleasant visibility. The final dehazed image is yielded by gating the important features of the derived inputs. To train the network, we introduce a multi-scale approach such that the halo artifacts can be avoided. Extensive experimental results on both synthetic and real-world images demonstrate that the proposed algorithm performs favorably against the state-of-the-art algorithms.

##### Abstract (translated by Google)
在本文中，我们提出了一种有效的算法，可以从朦胧的输入中直接恢复清晰的图像。所提出的算法取决于由编码器和解码器组成的端到端可训练神经网络。编码器被用于捕获导出的输入图像的上下文，而解码器被用来使用归因于编码器的学习表示来估计每个输入对最终去混合结果的贡献。构建的网络采用了一种新颖的基于融合的策略，通过应用白平衡（WB），对比度增强（CE）和伽玛校正（GC），从原始模糊图像中导出三个输入。我们基于这些不同输入之间的外观差异来计算像素方式的置信度图，以混合派生输入的信息并保持区域具有令人愉快的可见度。通过选通派生输入的重要特征来产生最终的去雾图像。为了训练网络，我们引入了一种多尺度方法，以避免光环伪影。在合成和现实世界的图像上的广泛的实验结果表明，所提出的算法对于最先进的算法有良好的效果。

##### URL
[http://arxiv.org/abs/1804.00213](http://arxiv.org/abs/1804.00213)

##### PDF
[http://arxiv.org/pdf/1804.00213](http://arxiv.org/pdf/1804.00213)

