---
layout: post
title: "Pulse Sequence Resilient Fast Brain Segmentation"
date: 2018-07-30 22:28:43
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Amod Jog, Bruce Fischl
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate automatic segmentation of brain anatomy from $T_1$-weighted~($T_1$-w) magnetic resonance images~(MRI) has been a computationally intensive bottleneck in neuroimaging pipelines, with state-of-the-art results obtained by unsupervised intensity modeling-based methods and multi-atlas registration and label fusion. With the advent of powerful supervised convolutional neural networks~(CNN)-based learning algorithms, it is now possible to produce a high quality brain segmentation within seconds. However, the very supervised nature of these methods makes it difficult to generalize them on data different from what they have been trained on. Modern neuroimaging studies are necessarily multi-center initiatives with a wide variety of acquisition protocols. Despite stringent protocol harmonization practices, it is not possible to standardize the whole gamut of MRI imaging parameters across scanners, field strengths, receive coils etc., that affect image contrast. In this paper we propose a CNN-based segmentation algorithm that, in addition to being highly accurate and fast, is also resilient to variation in the input $T_1$-w acquisition. Our approach relies on building approximate forward models of $T_1$-w pulse sequences that produce a typical test image. We use the forward models to augment the training data with test data specific training examples. These augmented data can be used to update and/or build a more robust segmentation model that is more attuned to the test data imaging properties. Our method generates highly accurate, state-of-the-art segmentation results~(overall Dice overlap=0.94), within seconds and is consistent across a wide-range of protocols.

##### Abstract (translated by Google)
从$ T_1 $加权〜（$ T_1 $ -w）磁共振图像〜（MRI）精确自动分割大脑解剖结构一直是神经成像管道中计算密集的瓶颈，通过无监督强度获得最先进的结果基于建模的方法和多图册注册和标签融合。随着基于强大的监督卷积神经网络（CNN）的学习算法的出现，现在可以在几秒钟内产生高质量的脑分割。然而，这些方法的监督性很强，很难将它们推广到与训练过程不同的数据上。现代神经影像学研究必然是具有多种采集方案的多中心计划。尽管协议协调实施严格，但不可能将扫描仪，场强，接收线圈等的整个MRI成像参数范围标准化，从而影响图像对比度。在本文中，我们提出了一种基于CNN的分割算法，该算法除了具有高度准确性和快速性外，还能够适应输入$ T_1 $ -w采集的变化。我们的方法依赖于构建产生典型测试图像的$ T_1 $ -w脉冲序列的近似正演模型。我们使用正向模型来使用特定于测试数据的训练示例来增强训练数据。这些增强数据可用于更新和/或构建更健壮的分割模型，其更适合于测试数据成像属性。我们的方法在几秒钟内生成高度准确的，最先进的分割结果〜（整体Dice重叠= 0.94），并且在各种协议中都是一致的。

##### URL
[http://arxiv.org/abs/1807.11598](http://arxiv.org/abs/1807.11598)

##### PDF
[http://arxiv.org/pdf/1807.11598](http://arxiv.org/pdf/1807.11598)

