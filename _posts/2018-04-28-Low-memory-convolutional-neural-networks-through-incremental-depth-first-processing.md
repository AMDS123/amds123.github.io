---
layout: post
title: "Low-memory convolutional neural networks through incremental depth-first processing"
date: 2018-04-28 03:03:45
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Jonathan Binas, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an incremental processing scheme for convolutional neural network (CNN) inference, targeted at embedded applications with limited memory budgets. Instead of processing layers one by one, individual input pixels are propagated through all parts of the network they can influence under the given structural constraints. This depth-first updating scheme comes with hard bounds on the memory footprint: the memory required is constant in the case of 1D input and proportional to the square root of the input dimension in the case of 2D input.

##### Abstract (translated by Google)
我们引入了卷积神经网络（CNN）推断的增量处理方案，针对内存预算有限的嵌入式应用。不是逐层处理图层，单个输入像素会在给定的结构约束条件下通过它们可以影响的网络的所有部分进行传播。这种深度优先的更新方案在内存占用方面存在着严格的界限：在2D输入的情况下，所需的内存在1D输入的情况下是恒定的并且与输入尺寸的平方根成比例。

##### URL
[https://arxiv.org/abs/1804.10727](https://arxiv.org/abs/1804.10727)

##### PDF
[https://arxiv.org/pdf/1804.10727](https://arxiv.org/pdf/1804.10727)

