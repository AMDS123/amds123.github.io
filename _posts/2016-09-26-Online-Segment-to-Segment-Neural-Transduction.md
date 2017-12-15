---
layout: post
title: "Online Segment to Segment Neural Transduction"
date: 2016-09-26 21:13:49
categories: arXiv_CL
tags: arXiv_CL Segmentation Attention Summarization Tracking
author: Lei Yu, Jan Buys, Phil Blunsom
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an online neural sequence to sequence model that learns to alternate between encoding and decoding segments of the input as it is read. By independently tracking the encoding and decoding representations our algorithm permits exact polynomial marginalization of the latent segmentation during training, and during decoding beam search is employed to find the best alignment path together with the predicted output sequence. Our model tackles the bottleneck of vanilla encoder-decoders that have to read and memorize the entire input sequence in their fixed-length hidden states before producing any output. It is different from previous attentive models in that, instead of treating the attention weights as output of a deterministic function, our model assigns attention weights to a sequential latent variable which can be marginalized out and permits online generation. Experiments on abstractive sentence summarization and morphological inflection show significant performance gains over the baseline encoder-decoders.

##### Abstract (translated by Google)
我们引入了一个在线神经序列序列模型，学习如何在输入的编码和解码段之间交替。通过独立地跟踪编码和解码表示，我们的算法允许在训练期间对潜在分段进行确切的多项式边缘化，并且在解码期间，使用波束搜索来与预测的输出序列一起找到最佳对准路径。我们的模型解决了在产生任何输出之前必须读取和记忆整个输入序列的固定长度隐藏状态的香草编码器 - 解码器的瓶颈。与以前的注意模型不同的是，我们的模型并没有将注意力权重视为一个确定性函数的输出，而是将注意力权重赋予一个可以被边缘化并允许在线生成的顺序潜变量。对抽象句汇总和形态学变化的实验显示，比基线编码器 - 译码器有显着的性能增益。

##### URL
[https://arxiv.org/abs/1609.08194](https://arxiv.org/abs/1609.08194)

##### PDF
[https://arxiv.org/pdf/1609.08194](https://arxiv.org/pdf/1609.08194)

