---
layout: post
title: "Advances in Very Deep Convolutional Neural Networks for LVCSR"
date: 2016-06-25 00:27:19
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition CNN Recognition
author: Tom Sercu, Vaibhava Goel
mathjax: true
---

* content
{:toc}

##### Abstract
Very deep CNNs with small 3x3 kernels have recently been shown to achieve very strong performance as acoustic models in hybrid NN-HMM speech recognition systems. In this paper we investigate how to efficiently scale these models to larger datasets. Specifically, we address the design choice of pooling and padding along the time dimension which renders convolutional evaluation of sequences highly inefficient. We propose a new CNN design without timepadding and without timepooling, which is slightly suboptimal for accuracy, but has two significant advantages: it enables sequence training and deployment by allowing efficient convolutional evaluation of full utterances, and, it allows for batch normalization to be straightforwardly adopted to CNNs on sequence data. Through batch normalization, we recover the lost peformance from removing the time-pooling, while keeping the benefit of efficient convolutional evaluation. We demonstrate the performance of our models both on larger scale data than before, and after sequence training. Our very deep CNN model sequence trained on the 2000h switchboard dataset obtains 9.4 word error rate on the Hub5 test-set, matching with a single model the performance of the 2015 IBM system combination, which was the previous best published result.

##### Abstract (translated by Google)
最近，已经证明具有小3×3内核的非常深的CNN在混合NN-HMM语音识别系统中作为声学模型获得了非常强的性能。在本文中，我们研究如何有效地将这些模型扩展到更大的数据集。具体而言，我们解决了时间维度上的汇集和填充的设计选择，这使得序列的卷积评估非常低效。我们提出了一种没有timepad的新的CNN设计，没有时间延迟，这对准确性来说稍微不是最理想的，但是有两个显着的优点：它允许对整个话语进行有效的卷积评估，从而能够进行序列训练和部署，并且允许批量规范直接通过CNN的序列数据。通过批量规范化，我们可以从删除时间库中恢复丢失的性能，同时保持高效的卷积评估的好处。我们证明了我们的模型在比以前更大规模的数据和序列训练之后的性能。我们在2000h交换机数据集上训练的非常深的CNN模型序列在Hub5测试集上获得了9.4个字的错误率，与单个模型匹配的是2015年IBM系统组合的性能，这是以前最好的公布结果。

##### URL
[https://arxiv.org/abs/1604.01792](https://arxiv.org/abs/1604.01792)

##### PDF
[https://arxiv.org/pdf/1604.01792](https://arxiv.org/pdf/1604.01792)

