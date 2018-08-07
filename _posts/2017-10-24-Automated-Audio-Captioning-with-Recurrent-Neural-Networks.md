---
layout: post
title: "Automated Audio Captioning with Recurrent Neural Networks"
date: 2017-10-24 11:36:08
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Classification
author: Konstantinos Drossos, Sharath Adavanne, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first approach to automated audio captioning. We employ an encoder-decoder scheme with an alignment model in between. The input to the encoder is a sequence of log mel-band energies calculated from an audio file, while the output is a sequence of words, i.e. a caption. The encoder is a multi-layered, bi-directional gated recurrent unit (GRU) and the decoder a multi-layered GRU with a classification layer connected to the last GRU of the decoder. The classification layer and the alignment model are fully connected layers with shared weights between timesteps. The proposed method is evaluated using data drawn from a commercial sound effects library, ProSound Effects. The resulting captions were rated through metrics utilized in machine translation and image captioning fields. Results from metrics show that the proposed method can predict words appearing in the original caption, but not always correctly ordered.

##### Abstract (translated by Google)
我们提出了第一种自动音频字幕方法。我们采用编码器 - 解码器方案，其间具有对准模型。编码器的输入是从音频文件计算的一系列对数梅尔能量，而输出是一系列单词，即字幕。编码器是多层双向门控循环单元（GRU），解码器是多层GRU，其分类层连接到解码器的最后GRU。分类层和对齐模型是完全连接的层，在时间步之间具有共享权重。使用从商业声音效果库ProSound Effects中提取的数据来评估所提出的方法。通过机器翻译和图像字幕字段中使用的度量标准对得到的字幕进行评级。指标的结果表明，所提出的方法可以预测出现在原始标题中的单词，但并不总是正确排序。

##### URL
[https://arxiv.org/abs/1706.10006](https://arxiv.org/abs/1706.10006)

##### PDF
[https://arxiv.org/pdf/1706.10006](https://arxiv.org/pdf/1706.10006)

