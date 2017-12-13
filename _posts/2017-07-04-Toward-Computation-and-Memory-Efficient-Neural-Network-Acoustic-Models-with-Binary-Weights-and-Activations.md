---
layout: post
title: "Toward Computation and Memory Efficient Neural Network Acoustic Models with Binary Weights and Activations"
date: 2017-07-04 17:03:20
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Inference Recognition
author: Liang Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network acoustic models have significantly advanced state of the art speech recognition over the past few years. However, they are usually computationally expensive due to the large number of matrix-vector multiplications and nonlinearity operations. Neural network models also require significant amounts of memory for inference because of the large model size. For these two reasons, it is challenging to deploy neural network based speech recognizers on resource-constrained platforms such as embedded devices. This paper investigates the use of binary weights and activations for computation and memory efficient neural network acoustic models. Compared to real-valued weight matrices, binary weights require much fewer bits for storage, thereby cutting down the memory footprint. Furthermore, with binary weights or activations, the matrix-vector multiplications are turned into addition and subtraction operations, which are computationally much faster and more energy efficient for hardware platforms. In this paper, we study the applications of binary weights and activations for neural network acoustic modeling, reporting encouraging results on the WSJ and AMI corpora.

##### Abstract (translated by Google)
神经网络声学模型在过去几年中具有显着先进的语音识别技术。然而，由于大量的矩阵向量乘法和非线性操作，它们通常在计算上是昂贵的。由于模型尺寸较大，神经网络模型也需要大量的内存来进行推理。出于这两个原因，将基于神经网络的语音识别器部署在资源受限的平台（如嵌入式设备）上是具有挑战性的。本文研究了使用二进制加权和激活计算和记忆效率的神经网络声学模型。与实值权重矩阵相比，二进制权重需要的位数少得多，从而减少了内存占用。此外，在二进制加权或激活的情况下，矩阵向量乘法被转化为加法和减法操作，这对于硬件平台在计算上更快且更节能。在本文中，我们研究神经网络声学建模的二进制权重和激活的应用，报告在WSJ和AMI语料库令人鼓舞的结果。

##### URL
[https://arxiv.org/abs/1706.09453](https://arxiv.org/abs/1706.09453)

##### PDF
[https://arxiv.org/pdf/1706.09453](https://arxiv.org/pdf/1706.09453)

