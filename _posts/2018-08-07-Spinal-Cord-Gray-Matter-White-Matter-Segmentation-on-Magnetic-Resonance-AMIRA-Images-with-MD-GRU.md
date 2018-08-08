---
layout: post
title: "Spinal Cord Gray Matter-White Matter Segmentation on Magnetic Resonance AMIRA Images with MD-GRU"
date: 2018-08-07 14:53:49
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN
author: Antal Horvath, Charidimos Tsagkas, Simon Andermatt, Simon Pezold, Katrin Parmar, Philippe Cattin
mathjax: true
---

* content
{:toc}

##### Abstract
The small butterfly shaped structure of spinal cord (SC) gray matter (GM) is challenging to image and to delinate from its surrounding white matter (WM). Segmenting GM is up to a point a trade-off between accuracy and precision. We propose a new pipeline for GM-WM magnetic resonance (MR) image acquisition and segmentation. We report superior results as compared to the ones recently reported in the SC GM segmentation challenge and show even better results using the averaged magnetization inversion recovery acquisitions (AMIRA) sequence. Scan-rescan experiments with the AMIRA sequence show high reproducibility in terms of Dice coefficient, Hausdorff distance and relative standard deviation. We use a recurrent neural network (RNN) with multi-dimensional gated recurrent units (MD-GRU) to train segmentation models on the AMIRA dataset of 855 slices. We added a generalized dice loss to the cross entropy loss that MD-GRU uses and were able to improve the results.

##### Abstract (translated by Google)
脊髓（SC）灰质（GM）的小蝴蝶形结构对图像具有挑战性，并且与周围的白质（WM）相区别。细分GM可以在精度和精度之间进行权衡。我们提出了一种新的GM-WM磁共振（MR）图像采集和分割管道。与最近在SC GM分段挑战中报告的结果相比，我们报告了更好的结果，并且使用平均磁化反转恢复采集（AMIRA）序列显示更好的结果。使用AMIRA序列的扫描重新扫描实验在Dice系数，Hausdorff距离和相对标准偏差方面显示出高重现性。我们使用具有多维门控循环单元（MD-GRU）的递归神经网络（RNN）来训练855个切片的AMIRA数据集上的分割模型。我们在MD-GRU使用的交叉熵损失中添加了广义骰子损失，并且能够改善结果。

##### URL
[http://arxiv.org/abs/1808.02408](http://arxiv.org/abs/1808.02408)

##### PDF
[http://arxiv.org/pdf/1808.02408](http://arxiv.org/pdf/1808.02408)

