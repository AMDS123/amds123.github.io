---
layout: post
title: "Performance Guaranteed Network Acceleration via High-Order Residual Quantization"
date: 2017-08-29 10:42:29
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Zefan Li, Bingbing Ni, Wenjun Zhang, Xiaokang Yang, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Input binarization has shown to be an effective way for network acceleration. However, previous binarization scheme could be regarded as simple pixel-wise thresholding operations (i.e., order-one approximation) and suffers a big accuracy loss. In this paper, we propose a highorder binarization scheme, which achieves more accurate approximation while still possesses the advantage of binary operation. In particular, the proposed scheme recursively performs residual quantization and yields a series of binary input images with decreasing magnitude scales. Accordingly, we propose high-order binary filtering and gradient propagation operations for both forward and backward computations. Theoretical analysis shows approximation error guarantee property of proposed method. Extensive experimental results demonstrate that the proposed scheme yields great recognition accuracy while being accelerated.

##### Abstract (translated by Google)
输入二值化已被证明是网络加速的有效方法。然而，先前的二值化方案可以被认为是简单的像素阈值操作（即，一阶近似）并且遭受较大的准确度损失。在本文中，我们提出了一个高阶二值化方案，它在实现更精确的近似的同时仍然具有二元运算的优点。具体来说，所提出的方案递归地执行残差量化并且产生具有递减量级的一系列二进制输入图像。因此，我们提出了高阶二进制滤波和梯度传播操作的前向和后向计算。理论分析表明了该方法的逼近误差保证性质。广泛的实验结果表明，该方案在加速的同时产生了较高的识别精度。

##### URL
[https://arxiv.org/abs/1708.08687](https://arxiv.org/abs/1708.08687)

##### PDF
[https://arxiv.org/pdf/1708.08687](https://arxiv.org/pdf/1708.08687)

