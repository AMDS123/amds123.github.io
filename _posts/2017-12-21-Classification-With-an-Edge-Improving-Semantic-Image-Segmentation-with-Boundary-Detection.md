---
layout: post
title: "Classification With an Edge: Improving Semantic Image Segmentation with Boundary Detection"
date: 2017-12-21 21:36:14
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification Detection
author: Dimitrios Marmanis, Konrad Schindler, Jan Dirk Wegner, Silvano Galliani, Mihai Datcu, Uwe Stilla
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end trainable deep convolutional neural network (DCNN) for semantic segmentation with built-in awareness of semantically meaningful boundaries. Semantic segmentation is a fundamental remote sensing task, and most state-of-the-art methods rely on DCNNs as their workhorse. A major reason for their success is that deep networks learn to accumulate contextual information over very large windows (receptive fields). However, this success comes at a cost, since the associated loss of effecive spatial resolution washes out high-frequency details and leads to blurry object boundaries. Here, we propose to counter this effect by combining semantic segmentation with semantically informed edge detection, thus making class-boundaries explicit in the model, First, we construct a comparatively simple, memory-efficient model by adding boundary detection to the Segnet encoder-decoder architecture. Second, we also include boundary detection in FCN-type models and set up a high-end classifier ensemble. We show that boundary detection significantly improves semantic segmentation with CNNs. Our high-end ensemble achieves &gt; 90% overall accuracy on the ISPRS Vaihingen benchmark.

##### Abstract (translated by Google)
我们提出了一个端到端的可训练深度卷积神经网络（DCNN）语义分割与语义上有意义的边界内置意识。语义分割是一项基本的遥感任务，大多数最先进的方法都依靠DCNN作为其主力。他们成功的一个主要原因是深度网络学会在非常大的窗口（感受域）上积累上下文信息。然而，这种成功是有代价的，因为有效空间分辨率的相关损失淘汰了高频细节并导致模糊的物体边界。在这里，我们提出通过结合语义分割和语义知识边缘检测来消除这种影响，从而使模型中的类边界变得清晰。首先，我们通过将边界检测添加到Segnet编码器 - 解码器来构造一个相对简单的，建筑。其次，在FCN型模型中也包括边界检测，并建立了一个高端的分类器集合。我们表明，边界检测显着提高了与CNN的语义分割。我们的高端合奏达到＆gt; ISPRS Vaihingen基准的整体准确率为90％。

##### URL
[http://arxiv.org/abs/1612.01337](http://arxiv.org/abs/1612.01337)

##### PDF
[http://arxiv.org/pdf/1612.01337](http://arxiv.org/pdf/1612.01337)

