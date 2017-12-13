---
layout: post
title: "MemNet: A Persistent Memory Network for Image Restoration"
date: 2017-08-07 17:20:58
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Attention CNN
author: Ying Tai, Jian Yang, Xiaoming Liu, Chunyan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, very deep convolutional neural networks (CNNs) have been attracting considerable attention in image restoration. However, as the depth grows, the long-term dependency problem is rarely realized for these very deep models, which results in the prior states/layers having little influence on the subsequent ones. Motivated by the fact that human thoughts have persistency, we propose a very deep persistent memory network (MemNet) that introduces a memory block, consisting of a recursive unit and a gate unit, to explicitly mine persistent memory through an adaptive learning process. The recursive unit learns multi-level representations of the current state under different receptive fields. The representations and the outputs from the previous memory blocks are concatenated and sent to the gate unit, which adaptively controls how much of the previous states should be reserved, and decides how much of the current state should be stored. We apply MemNet to three image restoration tasks, i.e., image denosing, super-resolution and JPEG deblocking. Comprehensive experiments demonstrate the necessity of the MemNet and its unanimous superiority on all three tasks over the state of the arts. Code is available at this https URL

##### Abstract (translated by Google)
最近，非常深的卷积神经网络（CNN）在图像恢复中已经引起了相当的重视。然而，随着深度的增加，这些非常深的模型很难实现长期的依赖问题，导致之前的状态/层次对后续的状态/层次影响不大。受到人类思维持续存在这一事实的启发，我们提出了一个非常深入的持久性内存网络（MemNet），它引入了一个由递归单元和门单元组成的内存块，通过自适应学习过程明确地挖掘持久性内存。递归单元学习不同感受域下的当前状态的多级表示。来自先前存储器块的表示和输出被连接并发送到门单元，该门单元自适应地控制应当保留多少以前的状态，并且决定应该存储多少当前状态。我们将MemNet应用于三个图像恢复任务，即图像去噪，超分辨率和JPEG去块。全面的实验证明了MemNet的必要性及其在三项任务上对艺术水平的一致优越性。代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1708.02209](https://arxiv.org/abs/1708.02209)

##### PDF
[https://arxiv.org/pdf/1708.02209](https://arxiv.org/pdf/1708.02209)

