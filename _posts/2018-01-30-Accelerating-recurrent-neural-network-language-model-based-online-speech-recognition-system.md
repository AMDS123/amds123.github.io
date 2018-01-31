---
layout: post
title: "Accelerating recurrent neural network language model based online speech recognition system"
date: 2018-01-30 06:58:50
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Recognition
author: Kyungmin Lee, Chiyoun Park, Namhoon Kim, Jaewon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents methods to accelerate recurrent neural network based language models (RNNLMs) for online speech recognition systems. Firstly, a lossy compression of the past hidden layer outputs (history vector) with caching is introduced in order to reduce the number of LM queries. Next, RNNLM computations are deployed in a CPU-GPU hybrid manner, which computes each layer of the model on a more advantageous platform. The added overhead by data exchanges between CPU and GPU is compensated through a frame-wise batching strategy. The performance of the proposed methods evaluated on LibriSpeech test sets indicates that the reduction in history vector precision improves the average recognition speed by 1.23 times with minimum degradation in accuracy. On the other hand, the CPU-GPU hybrid parallelization enables RNNLM based real-time recognition with a four times improvement in speed.

##### Abstract (translated by Google)
本文提出了加速在线语音识别系统的递归神经网络语言模型（RNNLM）的方法。首先，为了减少LM查询的次数，引入了具有缓存的过去的隐藏层输出（历史向量）的有损压缩。接下来，RNNLM计算以CPU-GPU混合方式部署，其在更有利的平台上计算模型的每一层。通过CPU和GPU之间的数据交换增加的开销通过逐帧批量策略进行补偿。在LibriSpeech测试集上评估的所提出方法的性能表明，历史向量精度的降低将平均识别速度提高了1.23倍，同时精度降低最小。另一方面，CPU-GPU混合并行化使基于RNNLM的实时识别速度提高了四倍。

##### URL
[http://arxiv.org/abs/1801.09866](http://arxiv.org/abs/1801.09866)

##### PDF
[http://arxiv.org/pdf/1801.09866](http://arxiv.org/pdf/1801.09866)

