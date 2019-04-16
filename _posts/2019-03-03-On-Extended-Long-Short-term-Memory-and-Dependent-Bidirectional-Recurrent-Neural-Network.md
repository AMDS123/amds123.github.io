---
layout: post
title: "On Extended Long Short-term Memory and Dependent Bidirectional Recurrent Neural Network"
date: 2019-03-03 04:30:02
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Prediction
author: Yuanhang Su, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we first analyze the memory behavior in three recurrent neural networks (RNN) cells; namely, the simple RNN (SRN), the long short-term memory (LSTM) and the gated recurrent unit (GRU), where the memory is defined as a function that maps previous elements in a sequence to the current output. Our study shows that all three of them suffer rapid memory decay. Then, to alleviate this effect, we introduce trainable scaling factors that act like an attention mechanism to adjust memory decay adaptively. The new design is called the extended LSTM (ELSTM). Finally, to design a system that is robust to previous erroneous predictions, we propose a dependent bidirectional recurrent neural network (DBRNN). Extensive experiments are conducted on different language tasks to demonstrate the superiority of the proposed ELSTM and DBRNN solutions. The ELTSM has achieved up to 30% increase in the labeled attachment score (LAS) as compared to LSTM and GRU in the dependency parsing (DP) task. Our models also outperform other state-of-the-art models such as bi-attention and convolutional sequence to sequence (convseq2seq) by close to 10% in the LAS.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.01686](https://arxiv.org/abs/1803.01686)

##### PDF
[https://arxiv.org/pdf/1803.01686](https://arxiv.org/pdf/1803.01686)

