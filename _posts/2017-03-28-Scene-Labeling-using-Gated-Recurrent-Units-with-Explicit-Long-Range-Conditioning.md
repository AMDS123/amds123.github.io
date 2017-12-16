---
layout: post
title: "Scene Labeling using Gated Recurrent Units with Explicit Long Range Conditioning"
date: 2017-03-28 05:12:44
categories: arXiv_CV
tags: arXiv_CV RNN
author: Qiangui Huang, Weiyue Wang, Kevin Zhou, Suya You, Ulrich Neumann
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural network (RNN), as a powerful contextual dependency modeling framework, has been widely applied to scene labeling problems. However, this work shows that directly applying traditional RNN architectures, which unfolds a 2D lattice grid into a sequence, is not sufficient to model structure dependencies in images due to the "impact vanishing" problem. First, we give an empirical analysis about the "impact vanishing" problem. Then, a new RNN unit named Recurrent Neural Network with explicit long range conditioning (RNN-ELC) is designed to alleviate this problem. A novel neural network architecture is built for scene labeling tasks where one of the variants of the new RNN unit, Gated Recurrent Unit with Explicit Long-range Conditioning (GRU-ELC), is used to model multi scale contextual dependencies in images. We validate the use of GRU-ELC units with state-of-the-art performance on three standard scene labeling datasets. Comprehensive experiments demonstrate that the new GRU-ELC unit benefits scene labeling problem a lot as it can encode longer contextual dependencies in images more effectively than traditional RNN units.

##### Abstract (translated by Google)
递归神经网络（RNN）作为一种强大的上下文依赖性建模框架，已被广泛应用于场景标注问题。然而，这项工作表明，直接应用传统的RNN体系结构，展开一个二维网格网格到一个序列，是不足以模型的结构依赖性，由于“影响消失”的问题。首先，我们对“冲击消失”问题进行实证分析。然后，设计一个新的带有显式长程调节的递归神经网络（RNN-ELC）的RNN单元来缓解这个问题。针对场景标记任务建立了一种新的神经网络结构，其中新的RNN单元的变体之一，具有显式长程调节的门控循环单元（GRU-ELC）用于对图像中的多尺度上下文相关性进行建模。我们验证了在三个标准场景标记数据集上使用具有最新性能的GRU-ELC单元的使用。全面的实验表明，新的GRU-ELC单元可以很好地利用场景标注问题，因为它可以比传统的RNN单元更有效地对图像中的更长的上下文依赖性进行编码。

##### URL
[https://arxiv.org/abs/1611.07485](https://arxiv.org/abs/1611.07485)

##### PDF
[https://arxiv.org/pdf/1611.07485](https://arxiv.org/pdf/1611.07485)

