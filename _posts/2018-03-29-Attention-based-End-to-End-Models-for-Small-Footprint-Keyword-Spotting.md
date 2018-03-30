---
layout: post
title: "Attention-based End-to-End Models for Small-Footprint Keyword Spotting"
date: 2018-03-29 03:32:59
categories: arXiv_CL
tags: arXiv_CL Attention RNN Detection
author: Changhao Shan, Junbo Zhang, Yujun Wang, Lei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an attention-based end-to-end neural approach for small-footprint keyword spotting (KWS), which aims to simplify the pipelines of building a production-quality KWS system. Our model consists of an encoder and an attention mechanism. The encoder transforms the input signal into a high level representation using RNNs. Then the attention mechanism weights the encoder features and generates a fixed-length vector. Finally, by linear transformation and softmax function, the vector becomes a score used for keyword detection. We also evaluate the performance of different encoder architectures, including LSTM, GRU and CRNN. Experiments on real-world wake-up data show that our approach outperforms the recent Deep KWS approach by a large margin and the best performance is achieved by CRNN. To be more specific, with ~84K parameters, our attention-based model achieves 1.02% false rejection rate (FRR) at 1.0 false alarm (FA) per hour.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于注意的端到端神经方法，用于小尺寸关键字点击（KWS），旨在简化构建产品质量KWS系统的流程。我们的模型由一个编码器和一个关注机制组成。编码器使用RNN将输入信号转换为高级表示。然后，关注机制对编码器特征进行加权并生成固定长度矢量。最后，通过线性变换和softmax函数，矢量成为用于关键字检测的分数。我们还评估不同编码器架构的性能，包括LSTM，GRU和CRNN。实际唤醒数据的实验表明，我们的方法大大优于近期的深KWS方法，CRNN可以取得最佳性能。更具体地说，使用约84K参数，我们的注意模型在每小时1.0次虚警（FA）时实现1.02％的错误拒绝率（FRR）。

##### URL
[http://arxiv.org/abs/1803.10916](http://arxiv.org/abs/1803.10916)

##### PDF
[http://arxiv.org/pdf/1803.10916](http://arxiv.org/pdf/1803.10916)

