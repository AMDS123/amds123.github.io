---
layout: post
title: "What to talk about and how? Selective Generation using LSTMs with Coarse-to-Fine Alignment"
date: 2016-01-08 23:07:32
categories: arXiv_CL
tags: arXiv_CL Salient Face RNN
author: Hongyuan Mei, Mohit Bansal, Matthew R. Walter
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end, domain-independent neural encoder-aligner-decoder model for selective generation, i.e., the joint task of content selection and surface realization. Our model first encodes a full set of over-determined database event records via an LSTM-based recurrent neural network, then utilizes a novel coarse-to-fine aligner to identify the small subset of salient records to talk about, and finally employs a decoder to generate free-form descriptions of the aligned, selected records. Our model achieves the best selection and generation results reported to-date (with 59% relative improvement in generation) on the benchmark WeatherGov dataset, despite using no specialized features or linguistic resources. Using an improved k-nearest neighbor beam filter helps further. We also perform a series of ablations and visualizations to elucidate the contributions of our key model components. Lastly, we evaluate the generalizability of our model on the RoboCup dataset, and get results that are competitive with or better than the state-of-the-art, despite being severely data-starved.

##### Abstract (translated by Google)
我们提出了一个选择性生成的端到端的，与领域无关的神经编码器 - 对准器 - 解码器模型，即内容选择和表面实现的共同任务。我们的模型首先通过一个基于LSTM的递归神经网络对一整套超定数据库事件记录进行编码，然后利用一种新颖的从粗到细的对准器来识别要讨论的显着记录的小子集，最后使用一个解码器生成对齐的选定记录的自由格式描述。尽管没有使用专门的功能或语言资源，但是我们的模型实现了迄今为止报告的最佳选择和发电结果（在发电量方面相对提高了59％）。使用改进的k近邻波束滤波器有助于进一步。我们还执行一系列消融和可视化来阐明我们关键模型组件的贡献。最后，我们评估模型在RoboCup数据集上的普遍性，得到与最新技术相比具有竞争优势的结果，尽管数据匮乏。

##### URL
[https://arxiv.org/abs/1509.00838](https://arxiv.org/abs/1509.00838)

##### PDF
[https://arxiv.org/pdf/1509.00838](https://arxiv.org/pdf/1509.00838)

