---
layout: post
title: "Double Path Networks for Sequence to Sequence Learning"
date: 2018-06-13 05:51:10
categories: arXiv_CL
tags: arXiv_CL Attention CNN
author: Kaitao Song, Xu Tan, Di He, Jianfeng Lu, Tao Qin, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder based Sequence to Sequence learning (S2S) has made remarkable progress in recent years. Different network architectures have been used in the encoder/decoder. Among them, Convolutional Neural Networks (CNN) and Self Attention Networks (SAN) are the prominent ones. The two architectures achieve similar performances but use very different ways to encode and decode context: CNN use convolutional layers to focus on the local connectivity of the sequence, while SAN uses self-attention layers to focus on global semantics. In this work we propose Double Path Networks for Sequence to Sequence learning (DPN-S2S), which leverage the advantages of both models by using double path information fusion. During the encoding step, we develop a double path architecture to maintain the information coming from different paths with convolutional layers and self-attention layers separately. To effectively use the encoded context, we develop a cross attention module with gating and use it to automatically pick up the information needed during the decoding step. By deeply integrating the two paths with cross attention, both types of information are combined and well exploited. Experiments show that our proposed method can significantly improve the performance of sequence to sequence learning over state-of-the-art systems.

##### Abstract (translated by Google)
基于编码器 - 解码器的序列到序列学习（S2S）近年来取得了显着的进步。编码器/解码器使用了不同的网络架构。其中，卷积神经网络（CNN）和自助注意网络（SAN）是其中的佼佼者。这两种体系结构实现类似的性能，但使用非常不同的方式对上下文进行编码和解码：CNN使用卷积层专注于序列的本地连接，而SAN使用自注意层专注于全局语义。在这项工作中，我们提出了序列到序列学习的双路径网络（DPN-S2S），它通过使用双路径信息融合来利用两种模型的优点。在编码过程中，我们开发了一种双路径体系结构，分别用卷积层和自我关注层来维护来自不同路径的信息。为了有效地使用编码的上下文，我们开发了一个带有门控的交叉注意模块，并使用它来自动获取解码步骤中所需的信息。通过对两条路径的深度整合进行相互关注，两种信息相结合并得到充分利用。实验表明，我们提出的方法可以显着提高序列对最先进系统的序列学习性能。

##### URL
[https://arxiv.org/abs/1806.04856](https://arxiv.org/abs/1806.04856)

##### PDF
[https://arxiv.org/pdf/1806.04856](https://arxiv.org/pdf/1806.04856)

