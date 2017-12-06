---
layout: post
title: "Video Captioning with Transferred Semantic Attributes"
date: 2016-11-23 07:59:59
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption CNN RNN
author: Yingwei Pan, Ting Yao, Houqiang Li, Tao Mei
---

* content
{:toc}

##### Abstract
Automatically generating natural language descriptions of videos plays a fundamental challenge for computer vision community. Most recent progress in this problem has been achieved through employing 2-D and/or 3-D Convolutional Neural Networks (CNN) to encode video content and Recurrent Neural Networks (RNN) to decode a sentence. In this paper, we present Long Short-Term Memory with Transferred Semantic Attributes (LSTM-TSA)---a novel deep architecture that incorporates the transferred semantic attributes learnt from images and videos into the CNN plus RNN framework, by training them in an end-to-end manner. The design of LSTM-TSA is highly inspired by the facts that 1) semantic attributes play a significant contribution to captioning, and 2) images and videos carry complementary semantics and thus can reinforce each other for captioning. To boost video captioning, we propose a novel transfer unit to model the mutually correlated attributes learnt from images and videos. Extensive experiments are conducted on three public datasets, i.e., MSVD, M-VAD and MPII-MD. Our proposed LSTM-TSA achieves to-date the best published performance in sentence generation on MSVD: 52.8% and 74.0% in terms of BLEU@4 and CIDEr-D. Superior results when compared to state-of-the-art methods are also reported on M-VAD and MPII-MD.

##### Abstract (translated by Google)
自动生成视频的自然语言描述对计算机视觉社区来说是一个根本性的挑战。通过使用二维和/或三维卷积神经网络（CNN）对视频内容进行编码和递归神经网络（RNN）来对句子进行解码，已经实现了这个问题的最新进展。在本文中，我们提出长时间记忆与转移语义属性（LSTM-TSA）---一种新颖的深层架构，将从图像和视频中学习的语义属性转换到CNN加上RNN框架，通过训练端到端的方式。 LSTM-TSA的设计受到以下事实的启发：1）语义属性对字幕有显着的贡献; 2）图像和视频带有互补的语义，因此可以互相补充字幕。为了增强视频字幕，我们提出了一种新颖的传输单元来模拟从图像和视频学习到的相互关联的属性。在三个公共数据集上进行了大量的实验，即MSVD，M-VAD和MPII-MD。我们提出的LSTM-TSA达到了最新发表的MSVD语句的最佳表现：BLEU4和CIDEr-D的表达率分别为52.8％和74.0％。 M-VAD和MPII-MD也报道了与最先进的方法相比的优越结果。

##### URL
[https://arxiv.org/abs/1611.07675](https://arxiv.org/abs/1611.07675)

