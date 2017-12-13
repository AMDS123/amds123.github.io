---
layout: post
title: "Max-Pooling Loss Training of Long Short-Term Memory Networks for Small-Footprint Keyword Spotting"
date: 2017-05-05 22:36:04
categories: arXiv_CV
tags: arXiv_CV RNN Memory_Networks
author: Ming Sun, Anirudh Raju, George Tucker, Sankaran Panchapagesan, Gengshen Fu, Arindam Mandal, Spyros Matsoukas, Nikko Strom, Shiv Vitaladevuni
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a max-pooling based loss function for training Long Short-Term Memory (LSTM) networks for small-footprint keyword spotting (KWS), with low CPU, memory, and latency requirements. The max-pooling loss training can be further guided by initializing with a cross-entropy loss trained network. A posterior smoothing based evaluation approach is employed to measure keyword spotting performance. Our experimental results show that LSTM models trained using cross-entropy loss or max-pooling loss outperform a cross-entropy loss trained baseline feed-forward Deep Neural Network (DNN). In addition, max-pooling loss trained LSTM with randomly initialized network performs better compared to cross-entropy loss trained LSTM. Finally, the max-pooling loss trained LSTM initialized with a cross-entropy pre-trained network shows the best performance, which yields $67.6\%$ relative reduction compared to baseline feed-forward DNN in Area Under the Curve (AUC) measure.

##### Abstract (translated by Google)
我们提出了一个基于最大池的损失函数来训练长时间短期记忆（LSTM）网络的小占用关键字点击（KWS），具有较低的CPU，内存和延迟要求。最大共享丢失训练可以通过用交叉熵损失训练的网络进行初始化来进一步指导。使用基于后验平滑的评估方法来测量关键词识别性能。我们的实验结果表明，使用交叉熵损失或最大池化损失进行训练的LSTM模型优于经过交叉熵损失训练的基线前馈深度神经网络（DNN）。此外，随机初始化网络训练LSTM的最大池丢失性能优于交叉熵损失训练LSTM。最后，利用交叉熵预训练网络初始化的最大共享丢失训练LSTM表现出最好的性能，相比基线前馈DNN在曲线下面积（AUC）度量，相对减少了67.6％。

##### URL
[https://arxiv.org/abs/1705.02411](https://arxiv.org/abs/1705.02411)

##### PDF
[https://arxiv.org/pdf/1705.02411](https://arxiv.org/pdf/1705.02411)

