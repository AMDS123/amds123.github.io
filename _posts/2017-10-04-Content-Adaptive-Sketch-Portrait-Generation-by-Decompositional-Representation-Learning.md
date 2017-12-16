---
layout: post
title: "Content-Adaptive Sketch Portrait Generation by Decompositional Representation Learning"
date: 2017-10-04 03:37:39
categories: arXiv_CV
tags: arXiv_CV Portrait_Generation Face Image_Generation CNN Represenation_Learning
author: Dongyu Zhang, Liang Lin, Tianshui Chen, Xian Wu, Wenwei Tan, Ebroul Izquierdo
mathjax: true
---

* content
{:toc}

##### Abstract
Sketch portrait generation benefits a wide range of applications such as digital entertainment and law enforcement. Although plenty of efforts have been dedicated to this task, several issues still remain unsolved for generating vivid and detail-preserving personal sketch portraits. For example, quite a few artifacts may exist in synthesizing hairpins and glasses, and textural details may be lost in the regions of hair or mustache. Moreover, the generalization ability of current systems is somewhat limited since they usually require elaborately collecting a dictionary of examples or carefully tuning features/components. In this paper, we present a novel representation learning framework that generates an end-to-end photo-sketch mapping through structure and texture decomposition. In the training stage, we first decompose the input face photo into different components according to their representational contents (i.e., structural and textural parts) by using a pre-trained Convolutional Neural Network (CNN). Then, we utilize a Branched Fully Convolutional Neural Network (BFCN) for learning structural and textural representations, respectively. In addition, we design a Sorted Matching Mean Square Error (SM-MSE) metric to measure texture patterns in the loss function. In the stage of sketch rendering, our approach automatically generates structural and textural representations for the input photo and produces the final result via a probabilistic fusion scheme. Extensive experiments on several challenging benchmarks suggest that our approach outperforms example-based synthesis algorithms in terms of both perceptual and objective metrics. In addition, the proposed method also has better generalization ability across dataset without additional training.

##### Abstract (translated by Google)
素描肖像的产生有益于数字娱乐和执法等广泛的应用。尽管已经做了大量的工作，但仍然没有解决一些问题，用于生成生动的，保留细节的个人素描肖像。例如，在合成发夹和眼镜中可能存在相当多的文物，并且在头发或小胡子的区域中可能丢失纹理细节。此外，现有系统的泛化能力有限，因为它们通常需要精心收集示例字典或仔细调整特征/组件。在本文中，我们提出了一种新颖的表示学习框架，通过结构和纹理分解生成端到端的照片素描映射。在训练阶段，我们首先使用预先训练的卷积神经网络（CNN）根据其表示内容（即，结构和纹理部分）将输入的人脸照片分解成不同的分量。然后，我们利用分支全卷积神经网络（BFCN）分别学习结构和纹理表示。此外，我们设计了一个排序匹配均方误差（SM-MSE）度量来测量损失函数中的纹理图案。在草图渲染阶段，我们的方法自动生成输入照片的结构和纹理表示，并通过概率融合方案产生最终结果。对几个具有挑战性的基准进行大量的实验表明，我们的方法在感知和客观指标方面优于基于示例的综合算法。另外，所提出的方法在没有额外训练的情况下也具有更好的跨数据集的泛化能力。

##### URL
[https://arxiv.org/abs/1710.01453](https://arxiv.org/abs/1710.01453)

##### PDF
[https://arxiv.org/pdf/1710.01453](https://arxiv.org/pdf/1710.01453)

