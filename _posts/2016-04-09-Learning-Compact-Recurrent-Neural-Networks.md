---
layout: post
title: "Learning Compact Recurrent Neural Networks"
date: 2016-04-09 19:09:22
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Zhiyun Lu, Vikas Sindhwani, Tara N. Sainath
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs), including long short-term memory (LSTM) RNNs, have produced state-of-the-art results on a variety of speech recognition tasks. However, these models are often too large in size for deployment on mobile devices with memory and latency constraints. In this work, we study mechanisms for learning compact RNNs and LSTMs via low-rank factorizations and parameter sharing schemes. Our goal is to investigate redundancies in recurrent architectures where compression can be admitted without losing performance. A hybrid strategy of using structured matrices in the bottom layers and shared low-rank factors on the top layers is found to be particularly effective, reducing the parameters of a standard LSTM by 75%, at a small cost of 0.3% increase in WER, on a 2,000-hr English Voice Search task.

##### Abstract (translated by Google)
递归神经网络（RNN），包括长期短期记忆（LSTM）RNN，已经在各种语音识别任务上产生了最新的结果。但是，这些模型的大小通常过大，无法在具有内存和延迟限制的移动设备上部署。在这项工作中，我们研究了通过低秩因子分解和参数共享方案来学习紧凑型RNN和LSTM的机制。我们的目标是调查经常性架构中的冗余，在这种架构中可以承认压缩而不会损失性能。发现在底层使用结构矩阵和在顶层共享低秩因子的混合策略是特别有效的，将WER的标准LSTM的参数降低了75％，WER增加了0.3％的小成本，在一个2000小时的英语语音搜索任务。

##### URL
[https://arxiv.org/abs/1604.02594](https://arxiv.org/abs/1604.02594)

##### PDF
[https://arxiv.org/pdf/1604.02594](https://arxiv.org/pdf/1604.02594)

