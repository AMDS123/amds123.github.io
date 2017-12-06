---
layout: post
title: "Automated Audio Captioning with Recurrent Neural Networks"
date: 2017-10-24 11:36:08
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Konstantinos Drossos, Sharath Adavanne, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first approach to automated audio captioning. We employ an encoder-decoder scheme with an alignment model in between. The input to the encoder is a sequence of log mel-band energies calculated from an audio file, while the output is a sequence of words, i.e. a caption. The encoder is a multi-layered, bi-directional gated recurrent unit (GRU) and the decoder a multi-layered GRU with a classification layer connected to the last GRU of the decoder. The classification layer and the alignment model are fully connected layers with shared weights between timesteps. The proposed method is evaluated using data drawn from a commercial sound effects library, ProSound Effects. The resulting captions were rated through metrics utilized in machine translation and image captioning fields. Results from metrics show that the proposed method can predict words appearing in the original caption, but not always correctly ordered.

##### Abstract (translated by Google)
我们提出了自动音频字幕的第一种方法。我们采用编码器 - 解码器方案，其间有一个对齐模型。编码器的输入是从一个音频文件计算出的一个日志梅尔带能量序列，而输出是一个字序列，即一个字幕。编码器是一个多层双向门控重发单元（GRU），解码器是一个多层GRU，分层连接到解码器的最后一个GRU。分类层和对齐模型是时间步长之间具有共享权重的完全连接的层。所提出的方法是使用从商业声音效果库ProSound Effects中得到的数据进行评估的。所得到的字幕通过机器翻译和图像字幕领域中使用的度量来评级。指标的结果表明，提出的方法可以预测出现在原始字幕中的单词，但并不总是正确排序。

##### URL
[https://arxiv.org/abs/1706.10006](https://arxiv.org/abs/1706.10006)

