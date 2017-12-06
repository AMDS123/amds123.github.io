---
layout: post
title: "Quantization and Training of Low Bit-Width Convolutional Neural Networks for Object Detection"
date: 2017-08-17 06:56:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Penghang Yin, Shuai Zhang, Yingyong Qi, Jack Xin
mathjax: true
---

* content
{:toc}

##### Abstract
We present LBW-Net, an efficient optimization based method for quantization and training of the low bit-width convolutional neural networks (CNNs). Specifically, we quantize the weights to zero or powers of two by minimizing the Euclidean distance between full-precision weights and quantized weights during backpropagation. We characterize the combinatorial nature of the low bit-width quantization problem. For 2-bit (ternary) CNNs, the quantization of $N$ weights can be done by an exact formula in $O(N\log N)$ complexity. When the bit-width is three and above, we further propose a semi-analytical thresholding scheme with a single free parameter for quantization that is computationally inexpensive. The free parameter is further determined by network retraining and object detection tests. LBW-Net has several desirable advantages over full-precision CNNs, including considerable memory savings, energy efficiency, and faster deployment. Our experiments on PASCAL VOC dataset show that compared with its 32-bit floating-point counterpart, the performance of the 6-bit LBW-Net is nearly lossless in the object detection tasks, and can even do better in some real world visual scenes, while empirically enjoying more than 4$\times$ faster deployment.

##### Abstract (translated by Google)
我们提出了LBW-Net，一种基于高效优化的低比特卷积神经网络（CNN）的量化和训练方法。具体而言，我们通过在反向传播期间最小化全精度权重和量化权重之间的欧几里得距离来将权重量化为零或二的幂。我们表征了低位宽量化问题的组合性质。对于2位（三元）CNN，可以用$ O（N \ log N）$复杂度中的精确公式完成$ N $权重的量化。当位宽为3以上时，我们进一步提出一种半解析阈值方案，其具有用于量化的单个自由参数，其在计算上是便宜的。自由参数进一步由网络再训练和对象检测测试来确定。与全精度CNN相比，LBW-Net具有一些令人满意的优势，包括大量的内存节省，能源效率和更快的部署。我们在PASCAL VOC数据集上的实验表明，与其32位浮点数相比，6位LBW-Net在物体检测任务中的性能几乎是无损的，在现实世界的视觉场景中甚至可以做的更好，而经验性地享受超过4美元/倍更快的部署。

##### URL
[https://arxiv.org/abs/1612.06052](https://arxiv.org/abs/1612.06052)

