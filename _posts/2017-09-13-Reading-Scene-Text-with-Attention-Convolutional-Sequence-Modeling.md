---
layout: post
title: "Reading Scene Text with Attention Convolutional Sequence Modeling"
date: 2017-09-13 12:57:47
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Classification Recognition
author: Yunze Gao (1 and 2), Yingying Chen (1 and 2), Jinqiao Wang (1 and 2), Hanqing Lu (1 and 2) ((1) National Lab of Pattern Recognition, Institute of Automation, Chinese Academy of Sciences, (2) University of Chinese Academy of Sciences)
mathjax: true
---

* content
{:toc}

##### Abstract
Reading text in the wild is a challenging task in the field of computer vision. Existing approaches mainly adopted Connectionist Temporal Classification (CTC) or Attention models based on Recurrent Neural Network (RNN), which is computationally expensive and hard to train. In this paper, we present an end-to-end Attention Convolutional Network for scene text recognition. Firstly, instead of RNN, we adopt the stacked convolutional layers to effectively capture the contextual dependencies of the input sequence, which is characterized by lower computational complexity and easier parallel computation. Compared to the chain structure of recurrent networks, the Convolutional Neural Network (CNN) provides a natural way to capture long-term dependencies between elements, which is 9 times faster than Bidirectional Long Short-Term Memory (BLSTM). Furthermore, in order to enhance the representation of foreground text and suppress the background noise, we incorporate the residual attention modules into a small densely connected network to improve the discriminability of CNN features. We validate the performance of our approach on the standard benchmarks, including the Street View Text, IIIT5K and ICDAR datasets. As a result, state-of-the-art or highly-competitive performance and efficiency show the superiority of the proposed approach.

##### Abstract (translated by Google)
在野外阅读文本是计算机视觉领域的一项具有挑战性的任务。现有方法主要采用基于递归神经网络（RNN）的连接主义时态分类（CTC）或注意模型，计算量大，难于训练。在本文中，我们提出了一个用于场景文本识别的端到端注意卷积网络。首先采用堆积卷积层来代替RNN，有效地捕获输入序列的上下文依赖关系，具有计算复杂度低，并行计算简单等特点。与循环网络的链结构相比，卷积神经网络（CNN）提供了一种自然的方法来捕获元素之间的长期依赖关系，比双向长时间短期记忆（BLSTM）快9倍。此外，为了提高前景文本的表示能力，抑制背景噪声，我们将残留注意模块纳入一个小型密集连接的网络中，以提高CNN特征的辨别能力。我们验证了我们在标准基准测试中的性能，包括街景文本，IIIT5K和ICDAR数据集。因此，最先进的或高度竞争的绩效和效率显示了所提出的方法的优越性。

##### URL
[https://arxiv.org/abs/1709.04303](https://arxiv.org/abs/1709.04303)

##### PDF
[https://arxiv.org/pdf/1709.04303](https://arxiv.org/pdf/1709.04303)

