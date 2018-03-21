---
layout: post
title: "LCANet: End-to-End Lipreading with Cascaded Attention-CTC"
date: 2018-03-13 18:04:10
categories: arXiv_CV
tags: arXiv_CV Attention Face Speech_Recognition CNN Recognition
author: Kai Xu, Dawei Li, Nick Cassimatis, Xiaolong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Machine lipreading is a special type of automatic speech recognition (ASR) which transcribes human speech by visually interpreting the movement of related face regions including lips, face, and tongue. Recently, deep neural network based lipreading methods show great potential and have exceeded the accuracy of experienced human lipreaders in some benchmark datasets. However, lipreading is still far from being solved, and existing methods tend to have high error rates on the wild data. In this paper, we propose LCANet, an end-to-end deep neural network based lipreading system. LCANet encodes input video frames using a stacked 3D convolutional neural network (CNN), highway network and bidirectional GRU network. The encoder effectively captures both short-term and long-term spatio-temporal information. More importantly, LCANet incorporates a cascaded attention-CTC decoder to generate output texts. By cascading CTC with attention, it partially eliminates the defect of the conditional independence assumption of CTC within the hidden neural layers, and this yields notably performance improvement as well as faster convergence. The experimental results show the proposed system achieves a 1.3% CER and 3.0% WER on the GRID corpus database, leading to a 12.3% improvement compared to the state-of-the-art methods.

##### Abstract (translated by Google)
机器唇部读取是一种特殊类型的自动语音识别（ASR），它通过视觉解释包括嘴唇，脸部和舌头在内的相关脸部区域的运动来转录人类语音。最近，基于深度神经网络的唇线阅读方法显示出巨大的潜力，并且在一些基准数据集中超过了经验丰富的人类唇线笔的准确性。然而，唇读仍远未解决，现有方法对野生数据的错误率往往较高。在本文中，我们提出LCANet，一种基于端到端深度神经网络的唇读系统。 LCANet使用堆叠的3D卷积神经网络（CNN），高速公路网络和双向GRU网络对输入视频帧进行编码。编码器有效捕获短时和长时空时信息。更重要的是，LCANet集成了一个级联注意-CTC解码器来生成输出文本。通过级联CTC注意力，它可以部分消除隐藏的神经层中CTC的条件独立性假设的缺陷，并且这产生显着的性能改进以及更快的收敛。实验结果表明，所提出的系统在GRID语料库数据库上实现了1.3％的CER和3.0％的WER，与最先进的方法相比，导致了12.3％的改进。

##### URL
[https://arxiv.org/abs/1803.04988](https://arxiv.org/abs/1803.04988)

##### PDF
[https://arxiv.org/pdf/1803.04988](https://arxiv.org/pdf/1803.04988)

