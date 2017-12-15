---
layout: post
title: "Compression of Deep Convolutional Neural Networks for Fast and Low Power Mobile Applications"
date: 2016-02-24 11:52:12
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Yong-Deok Kim, Eunhyeok Park, Sungjoo Yoo, Taelim Choi, Lu Yang, Dongjun Shin
mathjax: true
---

* content
{:toc}

##### Abstract
Although the latest high-end smartphone has powerful CPU and GPU, running deeper convolutional neural networks (CNNs) for complex tasks such as ImageNet classification on mobile devices is challenging. To deploy deep CNNs on mobile devices, we present a simple and effective scheme to compress the entire CNN, which we call one-shot whole network compression. The proposed scheme consists of three steps: (1) rank selection with variational Bayesian matrix factorization, (2) Tucker decomposition on kernel tensor, and (3) fine-tuning to recover accumulated loss of accuracy, and each step can be easily implemented using publicly available tools. We demonstrate the effectiveness of the proposed scheme by testing the performance of various compressed CNNs (AlexNet, VGGS, GoogLeNet, and VGG-16) on the smartphone. Significant reductions in model size, runtime, and energy consumption are obtained, at the cost of small loss in accuracy. In addition, we address the important implementation level issue on 1?1 convolution, which is a key operation of inception module of GoogLeNet as well as CNNs compressed by our proposed scheme.

##### Abstract (translated by Google)
尽管最新的高端智能手机拥有强大的CPU和GPU，但是在诸如移动设备上的ImageNet分类之类的复杂任务中运行更深的卷积神经网络（CNN）也是具有挑战性的。为了在移动设备上部署深度的CNN，我们提出了一个简单而有效的方案来压缩整个CNN，我们称之为一次全网压缩。该方案由三个步骤组成：（1）变分贝叶斯矩阵分解的秩选择，（2）核心张量上的Tucker分解，（3）微调恢复累计精度损失，每一步都可以很容易地实现公开的工具。我们通过在智能手机上测试各种压缩CNN（AlexNet，VGGS，GoogLeNet和VGG-16）的性能来证明所提议方案的有效性。在精确度损失小的代价下，可以大大减少模型大小，运行时间和能耗。另外，我们针对1-1卷积的重要实现水平问题，这是GoogLeNet起始模块的一个关键操作，也是我们提出的方案压缩的CNNs。

##### URL
[https://arxiv.org/abs/1511.06530](https://arxiv.org/abs/1511.06530)

##### PDF
[https://arxiv.org/pdf/1511.06530](https://arxiv.org/pdf/1511.06530)

