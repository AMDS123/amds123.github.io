---
layout: post
title: "Progressive Spatial Recurrent Neural Network for Intra Prediction"
date: 2018-07-06 03:13:55
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Yueyu Hu, Wenhan Yang, Mading Li, Jiaying Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Intra prediction is an important component of modern video codecs, which is able to efficiently squeeze out the spatial redundancy in video frames. With preceding pixels as the context, traditional intra prediction schemes generate linear predictions based on several predefined directions (i.e. modes) for blocks to be encoded. However, these modes are relatively simple and their predictions may fail when facing blocks with complex textures, which leads to additional bits encoding the residue. In this paper, we design a Progressive Spatial Recurrent Neural Network (PS-RNN) that learns to conduct intra prediction. Specifically, our PS-RNN consists of three spatial recurrent units and progressively generates predictions by passing information along from preceding contents to blocks to be encoded. To make our network generate predictions considering both distortion and bit-rate, we propose to use Sum of Absolute Transformed Difference (SATD) as the loss function to train PS-RNN since SATD is able to measure rate-distortion cost of encoding a residue block. Moreover, our method supports variable-block-size for intra prediction, which is more practical in real coding conditions. The proposed intra prediction scheme achieves on average 2.4% bit-rate reduction on variable-block-size settings under the same reconstruction quality compared with HEVC.

##### Abstract (translated by Google)
帧内预测是现代视频编解码器的重要组成部分，能够有效地挤出视频帧中的空间冗余。利用先前像素作为上下文，传统帧内预测方案基于要编码的块的若干预定义方向（即，模式）生成线性预测。然而，这些模式相对简单，并且当面对具有复杂纹理的块时，它们的预测可能失败，这导致编码残余物的附加位。在本文中，我们设计了一个渐进空间回归神经网络（PS-RNN），学习进行帧内预测。具体地说，我们的PS-RNN由三个空间循环单元组成，并通过将信息从前面的内容传递到要编码的块来逐步生成预测。为了使我们的网络生成考虑失真和比特率的预测，我们建议使用绝对变换差和（SATD）作为训练PS-RNN的损失函数，因为SATD能够测量编码残差块的速率 - 失真成本。 。此外，我们的方法支持用于帧内预测的可变块大小，这在实际编码条件下更实用。与HEVC相比，在相同的重建质量下，所提出的帧内预测方案在可变块大小设置上实现了平均2.4％的比特率降低。

##### URL
[http://arxiv.org/abs/1807.02232](http://arxiv.org/abs/1807.02232)

##### PDF
[http://arxiv.org/pdf/1807.02232](http://arxiv.org/pdf/1807.02232)

