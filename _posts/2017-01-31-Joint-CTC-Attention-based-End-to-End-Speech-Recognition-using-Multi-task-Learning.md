---
layout: post
title: "Joint CTC-Attention based End-to-End Speech Recognition using Multi-task Learning"
date: 2017-01-31 21:00:01
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Classification Recognition
author: Suyoun Kim, Takaaki Hori, Shinji Watanabe
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, there has been an increasing interest in end-to-end speech recognition that directly transcribes speech to text without any predefined alignments. One approach is the attention-based encoder-decoder framework that learns a mapping between variable-length input and output sequences in one step using a purely data-driven method. The attention model has often been shown to improve the performance over another end-to-end approach, the Connectionist Temporal Classification (CTC), mainly because it explicitly uses the history of the target character without any conditional independence assumptions. However, we observed that the performance of the attention has shown poor results in noisy condition and is hard to learn in the initial training stage with long input sequences. This is because the attention model is too flexible to predict proper alignments in such cases due to the lack of left-to-right constraints as used in CTC. This paper presents a novel method for end-to-end speech recognition to improve robustness and achieve fast convergence by using a joint CTC-attention model within the multi-task learning framework, thereby mitigating the alignment issue. An experiment on the WSJ and CHiME-4 tasks demonstrates its advantages over both the CTC and attention-based encoder-decoder baselines, showing 5.4-14.6% relative improvements in Character Error Rate (CER).

##### Abstract (translated by Google)
最近，对端对端语音识别的兴趣日益增长，它直接将语音转换成文本而没有任何预定义的对齐。一种方法是基于注意力的编码器 - 解码器框架，其使用纯粹的数据驱动方法一步学习可变长度输入和输出序列之间的映射。注意模型经常被证明可以提高另一种端对端方法连接主义时间分类（CTC）的性能，主要是因为它明确地使用了目标字符的历史，而没有任何条件独立性假设。然而，我们观察到注意的表现在嘈杂的条件下表现不佳，并且在长输入序列的初始训练阶段难以学习。这是因为注意模型过于灵活，无法预测这种情况下的正确对齐，因为CTC中缺少从左到右的约束。本文提出了一种端到端语音识别的新方法，通过在多任务学习框架内使用联合CTC关注模型来提高鲁棒性并实现快速收敛，从而缓解对齐问题。对WSJ和CHiME-4任务的实验证明，其优于CTC和基于注意力的编码器 - 解码器基线的优点，在字符错误率（CER）方面显示5.4-14.6％的相对改进。

##### URL
[https://arxiv.org/abs/1609.06773](https://arxiv.org/abs/1609.06773)

##### PDF
[https://arxiv.org/pdf/1609.06773](https://arxiv.org/pdf/1609.06773)

