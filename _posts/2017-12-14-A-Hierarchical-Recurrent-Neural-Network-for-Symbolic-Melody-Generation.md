---
layout: post
title: "A Hierarchical Recurrent Neural Network for Symbolic Melody Generation"
date: 2017-12-14 15:11:09
categories: arXiv_SD
tags: arXiv_SD RNN
author: Jian Wu, Changran Hu, Yulong Wang, Xiaolin Hu, Jun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, neural networks have been used to generate music pieces, especially symbolic melody. However, the long-term structure in the melody has posed great difficulty for designing a good model. In this paper, we present a hierarchical recurrent neural network for melody generation, which consists of three Long-Short-Term-Memory (LSTM) subnetworks working in a coarse-to-fine manner. Specifically, the three subnetworks generate bar profiles, beat profiles and notes in turn, and the output of the high-level subnetworks are fed into the low-level subnetworks, serving as guidance for generating the finer time-scale melody components. Two human behavior experiments demonstrate the advantage of this structure over the single-layer LSTM which attempts to learn all hidden structures in melodies. In the third human behavior experiment, subjects are asked to judge whether the generated melody is composed by human or computer. The results show that 33.69% of the generated melodies are wrongly classified as human composed.

##### Abstract (translated by Google)
近年来，神经网络已被用于生成音乐作品，尤其是象征旋律。但是，旋律的长期结构给设计一个好的模型带来了很大的困难。在本文中，我们提出了一种用于旋律生成的分层递归神经网络，其由三个长 - 短期存储（LSTM）子网以粗到细的方式工作。具体而言，三个子网依次生成条形轮廓，节拍轮廓和音符，并将高级子网络的输出馈送到低级子网络，作为生成更精细的时标旋律分量的指导。两个人类行为实验证明了这种结构优于单层LSTM的优点，该单层LSTM试图学习旋律中的所有隐藏结构。在第三人类行为实验中，要求被试判断生成的旋律是由人还是计算机组成。结果表明，所产生的旋律有33.69％被错误地归类为人类组成。

##### URL
[http://arxiv.org/abs/1712.05274](http://arxiv.org/abs/1712.05274)

##### PDF
[http://arxiv.org/pdf/1712.05274](http://arxiv.org/pdf/1712.05274)

