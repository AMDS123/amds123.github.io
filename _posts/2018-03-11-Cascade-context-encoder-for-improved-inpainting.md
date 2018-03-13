---
layout: post
title: "Cascade context encoder for improved inpainting"
date: 2018-03-11 20:31:39
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Bartosz Zieliński, Łukasz Struski, Marek Śmieja, Jacek Tabor
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we analyze if cascade usage of the context encoder with increasing input can improve the results of the inpainting. For this purpose, we train context encoder for 64x64 pixels images in a standard way and use its resized output to fill in the missing input region of the 128x128 context encoder, both in training and evaluation phase. As the result, the inpainting is visibly more plausible. In order to thoroughly verify the results, we introduce normalized squared-distortion, a measure for quantitative inpainting evaluation, and we provide its mathematical explanation. This is the first attempt to formalize the inpainting measure, which is based on the properties of latent feature representation, instead of L2 reconstruction loss.

##### Abstract (translated by Google)
在本文中，我们分析如果使用增加输入的上下文编码器的级联使用可以改善修复的结果。为此，我们以标准方式训练64x64像素图像的上下文编码器，并在训练和评估阶段使用调整后的输出来填充128x128上下文编码器的缺失输入区域。结果，修改显然更可信。为了彻底验证结果，我们引入归一化平方失真（一种用于量化修复评估的量度），并提供其数学解释。这是第一次尝试将修复措施形式化，该修复措施基于潜在特征表示的属性，而不是L2重建损失。

##### URL
[https://arxiv.org/abs/1803.04033](https://arxiv.org/abs/1803.04033)

##### PDF
[https://arxiv.org/pdf/1803.04033](https://arxiv.org/pdf/1803.04033)

