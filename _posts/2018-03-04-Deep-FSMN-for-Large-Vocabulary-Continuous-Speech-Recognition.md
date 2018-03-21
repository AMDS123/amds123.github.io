---
layout: post
title: "Deep-FSMN for Large Vocabulary Continuous Speech Recognition"
date: 2018-03-04 11:08:16
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Memory_Networks Recognition
author: Shiliang Zhang, Ming Lei, Zhijie Yan, Lirong Dai
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an improved feedforward sequential memory networks (FSMN) architecture, namely Deep-FSMN (DFSMN), by introducing skip connections between memory blocks in adjacent layers. These skip connections enable the information flow across different layers and thus alleviate the gradient vanishing problem when building very deep structure. As a result, DFSMN significantly benefits from these skip connections and deep structure. We have compared the performance of DFSMN to BLSTM both with and without lower frame rate (LFR) on several large speech recognition tasks, including English and Mandarin. Experimental results shown that DFSMN can consistently outperform BLSTM with dramatic gain, especially trained with LFR using CD-Phone as modeling units. In the 2000 hours Fisher (FSH) task, the proposed DFSMN can achieve a word error rate of 9.4% by purely using the cross-entropy criterion and decoding with a 3-gram language model, which achieves a 1.5% absolute improvement compared to the BLSTM. In a 20000 hours Mandarin recognition task, the LFR trained DFSMN can achieve more than 20% relative improvement compared to the LFR trained BLSTM. Moreover, we can easily design the lookahead filter order of the memory blocks in DFSMN to control the latency for real-time applications.

##### Abstract (translated by Google)
在本文中，我们通过在相邻层的存储器块之间引入跳过连接，提出了一种改进的前馈顺序存储器网络（FSMN）架构，即Deep-FSMN（DFSMN）。这些跳转连接使信息能够跨越不同的层，从而在构建非常深的结构时减轻梯度消失问题。因此，DFSMN显着受益于这些跳转连接和深层结构。我们已经比较了DFSMN和BLSTM在包括英语和普通话在内的几种大型语音识别任务时的性能，有无帧率（LFR）。实验结果表明，DFSMN可以持续优于BLSTM，并获得巨大的收益，尤其是使用CD-Phone作为建模单元进行LFR训练。在2000小时Fisher（FSH）任务中，通过纯粹使用交叉熵准则并使用3-gram语言模型进行解码，所提出的DFSMN可以实现9.4％的字错误率，相比于BLSTM。在20000小时的普通话识别任务中，与LFR训练的BLSTM相比，LFR训练的DFSMN可以实现超过20％的相对改进。此外，我们可以轻松设计DFSMN中内存块的先行过滤顺序，以控制实时应用程序的延迟。

##### URL
[https://arxiv.org/abs/1803.05030](https://arxiv.org/abs/1803.05030)

##### PDF
[https://arxiv.org/pdf/1803.05030](https://arxiv.org/pdf/1803.05030)

