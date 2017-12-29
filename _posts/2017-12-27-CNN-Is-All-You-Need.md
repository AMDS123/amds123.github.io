---
layout: post
title: "CNN Is All You Need"
date: 2017-12-27 19:49:09
categories: arXiv_CL
tags: arXiv_CL CNN RNN Deep_Learning
author: Qiming Chen, Ren Wu
mathjax: true
---

* content
{:toc}

##### Abstract
The Convolution Neural Network (CNN) has demonstrated the unique advantage in audio, image and text learning; recently it has also challenged Recurrent Neural Networks (RNNs) with long short-term memory cells (LSTM) in sequence-to-sequence learning, since the computations involved in CNN are easily parallelizable whereas those involved in RNN are mostly sequential, leading to a performance bottleneck. However, unlike RNN, the native CNN lacks the history sensitivity required for sequence transformation; therefore enhancing the sequential order awareness, or position-sensitivity, becomes the key to make CNN the general deep learning model. In this work we introduce an extended CNN model with strengthen position-sensitivity, called PoseNet. A notable feature of PoseNet is the asymmetric treatment of position information in the encoder and the decoder. Experiments shows that PoseNet allows us to improve the accuracy of CNN based sequence-to-sequence learning significantly, achieving around 33-36 BLEU scores on the WMT 2014 English-to-German translation task, and around 44-46 BLEU scores on the English-to-French translation task.

##### Abstract (translated by Google)
卷积神经网络（CNN）在音频，图像和文本学习方面表现出独特的优势;最近它也在顺序到序列的学习中对具有长期短期记忆细胞（LSTM）的递归神经网络（RNN）提出了挑战，因为涉及CNN的计算很容易并行化，而涉及RNN的计算大部分是连续的，导致性能瓶颈。然而，与RNN不同，本地CNN缺乏序列转换所需的历史敏感性;因此增强顺序意识或位置敏感性成为CNN成为一般深度学习模式的关键。在这项工作中，我们引入一个扩展的CNN模型，加强位置灵敏度，称为PoseNet。 PoseNet的一个显着特点是编码器和解码器中位置信息的不对称处理。实验表明，PoseNet使我们能够显着提高基于CNN的序列到序列学习的准确性，在WMT 2014英语到德语翻译任务中获得大约33-36个BLEU分数，并且英语44-46个BLEU分数法语翻译任务。

##### URL
[http://arxiv.org/abs/1712.09662](http://arxiv.org/abs/1712.09662)

##### PDF
[http://arxiv.org/pdf/1712.09662](http://arxiv.org/pdf/1712.09662)

