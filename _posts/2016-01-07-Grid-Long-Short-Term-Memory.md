---
layout: post
title: "Grid Long Short-Term Memory"
date: 2016-01-07 18:39:48
categories: arXiv_CL
tags: arXiv_CL RNN Prediction
author: Nal Kalchbrenner, Ivo Danihelka, Alex Graves
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces Grid Long Short-Term Memory, a network of LSTM cells arranged in a multidimensional grid that can be applied to vectors, sequences or higher dimensional data such as images. The network differs from existing deep LSTM architectures in that the cells are connected between network layers as well as along the spatiotemporal dimensions of the data. The network provides a unified way of using LSTM for both deep and sequential computation. We apply the model to algorithmic tasks such as 15-digit integer addition and sequence memorization, where it is able to significantly outperform the standard LSTM. We then give results for two empirical tasks. We find that 2D Grid LSTM achieves 1.47 bits per character on the Wikipedia character prediction benchmark, which is state-of-the-art among neural approaches. In addition, we use the Grid LSTM to define a novel two-dimensional translation model, the Reencoder, and show that it outperforms a phrase-based reference system on a Chinese-to-English translation task.

##### Abstract (translated by Google)
本文介绍了网格长期短期记忆（LSTM）网格，它是一个以多维网格排列的LSTM网格，可以应用于矢量，序列或图像等高维数据。该网络与现有的深层LSTM架构不同之处在于，单元连接在网络层之间以及数据的时空维度上。网络提供了使用LSTM进行深度和顺序计算的统一方式。我们将该模型应用于算法任务，例如15位整数加法和序列记忆，它能够显着地超越标准LSTM。然后，我们给出两个经验任务的结果。我们发现，二维网格LSTM在维基百科字符预测基准上达到每个字符1.47位，这是神经方法中的最新技术。另外，我们使用Grid LSTM来定义一个新颖的二维翻译模型Reencoder，并且表明在一个中英文翻译任务中它比一个基于短语的参考系统更胜一筹。

##### URL
[https://arxiv.org/abs/1507.01526](https://arxiv.org/abs/1507.01526)

##### PDF
[https://arxiv.org/pdf/1507.01526](https://arxiv.org/pdf/1507.01526)

