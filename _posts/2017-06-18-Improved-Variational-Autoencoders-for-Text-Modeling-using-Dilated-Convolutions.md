---
layout: post
title: "Improved Variational Autoencoders for Text Modeling using Dilated Convolutions"
date: 2017-06-18 00:31:34
categories: arXiv_SD
tags: arXiv_SD RNN Language_Model
author: Zichao Yang, Zhiting Hu, Ruslan Salakhutdinov, Taylor Berg-Kirkpatrick
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work on generative modeling of text has found that variational auto-encoders (VAE) incorporating LSTM decoders perform worse than simpler LSTM language models (Bowman et al., 2015). This negative result is so far poorly understood, but has been attributed to the propensity of LSTM decoders to ignore conditioning information from the encoder. In this paper, we experiment with a new type of decoder for VAE: a dilated CNN. By changing the decoder's dilation architecture, we control the effective context from previously generated words. In experiments, we find that there is a trade off between the contextual capacity of the decoder and the amount of encoding information used. We show that with the right decoder, VAE can outperform LSTM language models. We demonstrate perplexity gains on two datasets, representing the first positive experimental result on the use VAE for generative modeling of text. Further, we conduct an in-depth investigation of the use of VAE (with our new decoding architecture) for semi-supervised and unsupervised labeling tasks, demonstrating gains over several strong baselines.

##### Abstract (translated by Google)
最近有关文本生成建模的研究发现，包含LSTM解码器的变分自动编码器（VAE）比简单的LSTM语言模型表现得更差（Bowman等，2015）。这个负面结果到目前为止还不是很清楚，但归结于LSTM解码器忽视来自编码器的调节信息的倾向。在本文中，我们尝试了一种新型的VAE解码器：CNN扩张。通过改变解码器的扩展架构，我们控制了先前生成的单词的有效上下文。在实验中，我们发现在解码器的上下文容量和所使用的编码信息量之间存在权衡。我们证明，使用正确的解码器，VAE可以胜过LSTM语言模型。我们证明了两个数据集的困惑增益，代表了使用VAE进行文本生成建模的第一个正面实验结果。此外，我们深入研究了VAE（使用我们新的解码架构）在半监督和无监督的标签任务中的使用情况，证明了在几个强大的基线上的收益。

##### URL
[https://arxiv.org/abs/1702.08139](https://arxiv.org/abs/1702.08139)

##### PDF
[https://arxiv.org/pdf/1702.08139](https://arxiv.org/pdf/1702.08139)

