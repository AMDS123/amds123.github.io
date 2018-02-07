---
layout: post
title: "Byte-Level Recursive Convolutional Auto-Encoder for Text"
date: 2018-02-06 06:47:09
categories: arXiv_CL
tags: arXiv_CL Text_Generation CNN
author: Xiang Zhang, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
This article proposes to auto-encode text at byte-level using convolutional networks with a recursive architecture. The motivation is to explore whether it is possible to have scalable and homogeneous text generation at byte-level in a non-sequential fashion through the simple task of auto-encoding. We show that non-sequential text generation from a fixed-length representation is not only possible, but also achieved much better auto-encoding results than recurrent networks. The proposed model is a multi-stage deep convolutional encoder-decoder framework using residual connections, containing up to 160 parameterized layers. Each encoder or decoder contains a shared group of modules that consists of either pooling or upsampling layers, making the network recursive in terms of abstraction levels in representation. Results for 6 large-scale paragraph datasets are reported, in 3 languages including Arabic, Chinese and English. Analyses are conducted to study several properties of the proposed model.

##### Abstract (translated by Google)
本文提出使用具有递归体系结构的卷积网络在字节级自动编码文本。其动机是通过简单的自动编码任务来探索是否有可能在字节级以非顺序的方式生成可伸缩的同类文本。我们表明，从固定长度的表示中生成非序列文本不仅是可能的，而且还实现了比经常性网络更好的自动编码结果。所提出的模型是使用残余连接的多级深度卷积编码器 - 解码器框架，包含多达160个参数化层。每个编码器或解码器都包含共享的一组模块，这些模块由池或上采样层组成，从而使网络在表示的抽象层次上递归。报告了6个大规模段落数据集的结果，包括阿拉伯文，中文和英文3种语言。进行分析以研究所提出的模型的若干性质。

##### URL
[http://arxiv.org/abs/1802.01817](http://arxiv.org/abs/1802.01817)

##### PDF
[http://arxiv.org/pdf/1802.01817](http://arxiv.org/pdf/1802.01817)

