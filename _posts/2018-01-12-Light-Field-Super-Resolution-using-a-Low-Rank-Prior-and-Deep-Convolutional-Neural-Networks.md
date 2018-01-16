---
layout: post
title: "Light Field Super-Resolution using a Low-Rank Prior and Deep Convolutional Neural Networks"
date: 2018-01-12 21:02:24
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Embedding CNN
author: Reuben A. Farrugia, Christine Guillemot
mathjax: true
---

* content
{:toc}

##### Abstract
Light field imaging has recently known a regain of interest due to the availability of practical light field capturing systems that offer a wide range of applications in the field of computer vision. However, capturing high-resolution light fields remains technologically challenging since the increase in angular resolution is often accompanied by a significant reduction in spatial resolution. This paper describes a learning-based spatial light field super-resolution method that allows the restoration of the entire light field with consistency across all sub-aperture images. The algorithm first uses optical flow to align the light field and then reduces its angular dimension using low-rank approximation. We then consider the linearly independent columns of the resulting low-rank model as an embedding, which is restored using a deep convolutional neural network (DCNN). The super-resolved embedding is then used to reconstruct the remaining sub-aperture images. The original disparities are restored using inverse warping where missing pixels are approximated using a novel light field inpainting algorithm. Experimental results show that the proposed method outperforms existing light field super-resolution algorithms, achieving PSNR gains of 0.23 dB over the second best performing method. This performance can be further improved using iterative back-projection as a post-processing step.

##### Abstract (translated by Google)
由于可用的实际光场捕获系统在光学领域提供了广泛的应用，光场成像近来已经重新引起人们的兴趣。然而，捕获高分辨率的光场仍然是技术上的挑战，因为角分辨率的增加通常伴随着空间分辨率的显着降低。本文描述了一种基于学习的空间光场超分辨率方法，允许整个光场在所有子孔径图像中保持一致性。该算法首先使用光流来对准光场，然后使用低秩近似来减小其角度尺寸。然后，我们将所得到的低秩模型的线性无关列视为一个嵌入，使用深度卷积神经网络（DCNN）进行恢复。然后使用超分辨嵌入来重建剩余的子孔径图像。使用反向扭曲来恢复原始差异，其中利用新颖的光场修补算法近似丢失像素。实验结果表明，所提出的方法优于现有的光场超分辨率算法，与次优性能方法相比，PSNR增益为0.23 dB。使用迭代反投影作为后处理步骤，可以进一步提高性能。

##### URL
[https://arxiv.org/abs/1801.04314](https://arxiv.org/abs/1801.04314)

##### PDF
[https://arxiv.org/pdf/1801.04314](https://arxiv.org/pdf/1801.04314)

