---
layout: post
title: "Parallel Multi-Dimensional LSTM, With Application to Fast Biomedical Volumetric Image Segmentation"
date: 2015-06-24 16:26:51
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN
author: Marijn F. Stollenga, Wonmin Byeon, Marcus Liwicki, Juergen Schmidhuber
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) can be shifted across 2D images or 3D videos to segment them. They have a fixed input size and typically perceive only small local contexts of the pixels to be classified as foreground or background. In contrast, Multi-Dimensional Recurrent NNs (MD-RNNs) can perceive the entire spatio-temporal context of each pixel in a few sweeps through all pixels, especially when the RNN is a Long Short-Term Memory (LSTM). Despite these theoretical advantages, however, unlike CNNs, previous MD-LSTM variants were hard to parallelize on GPUs. Here we re-arrange the traditional cuboid order of computations in MD-LSTM in pyramidal fashion. The resulting PyraMiD-LSTM is easy to parallelize, especially for 3D data such as stacks of brain slice images. PyraMiD-LSTM achieved best known pixel-wise brain image segmentation results on MRBrainS13 (and competitive results on EM-ISBI12).

##### Abstract (translated by Google)
卷积神经网络（CNN）可以在2D图像或3D视频中移动来分割它们。他们有一个固定的输入大小，通常只感知像素的小本地上下文被分类为前景或背景。相反，多维递归神经网络（MD-RNN）可以通过所有像素在一些扫描中感知每个像素的整个时空上下文，特别是当RNN是长期短期存储器（LSTM）时。尽管有这些理论优势，但是，与CNN不同的是，之前的MD-LSTM变体很难在GPU上并行化。这里我们用金字塔方式重新排列MD-LSTM中传统的长方体计算顺序。由此产生的PyraMiD-LSTM易于并行化，特别是对于3D数据，例如大脑切片图像的堆叠。 PyraMiD-LSTM在MRBrainS13上实现了众所周知的逐像素脑图像分割结果（和EM-ISBI12上的竞争结果）。

##### URL
[https://arxiv.org/abs/1506.07452](https://arxiv.org/abs/1506.07452)

##### PDF
[https://arxiv.org/pdf/1506.07452](https://arxiv.org/pdf/1506.07452)

