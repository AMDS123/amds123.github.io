---
layout: post
title: "Advancing Acoustic-to-Word CTC Model"
date: 2018-03-15 01:25:17
categories: arXiv_CL
tags: arXiv_CL Attention Classification Language_Model
author: Jinyu Li, Guoli Ye, Amit Das, Rui Zhao, Yifan Gong
mathjax: true
---

* content
{:toc}

##### Abstract
The acoustic-to-word model based on the connectionist temporal classification (CTC) criterion was shown as a natural end-to-end (E2E) model directly targeting words as output units. However, the word-based CTC model suffers from the out-of-vocabulary (OOV) issue as it can only model limited number of words in the output layer and maps all the remaining words into an OOV output node. Hence, such a word-based CTC model can only recognize the frequent words modeled by the network output nodes. Our first attempt to improve the acoustic-to-word model is a hybrid CTC model which consults a letter-based CTC when the word-based CTC model emits OOV tokens during testing time. Then, we propose a much better solution by training a mixed-unit CTC model which decomposes all the OOV words into sequences of frequent words and multi-letter units. Evaluated on a 3400 hours Microsoft Cortana voice assistant task, the final acoustic-to-word solution improves the baseline word-based CTC by relative 12.09% word error rate (WER) reduction when combined with our proposed attention CTC. Such an E2E model without using any language model (LM) or complex decoder outperforms the traditional context-dependent phoneme CTC which has strong LM and decoder by relative 6.79%.

##### Abstract (translated by Google)
基于连接主义时间分类（CTC）标准的声 - 词模型被表示为直接将词作为输出单元的自然端到端（E2E）模型。然而，基于单词的CTC模型遭遇词汇外（OOV）问题，因为它只能模拟输出层中有限数量的单词，并将所有剩余单词映射到OOV输出节点。因此，这种基于字的CTC模型只能识别由网络输出节点建模的频繁字。我们首次尝试改进声 - 字模型是一种混合CTC模型，当基于字的CTC模型在测试期间发出OOV标记时，它会咨询基于字母的CTC。然后，我们通过训练混合单元CTC模型提出了一个更好的解决方案，该模型将所有OOV单词分解为频繁单词和多字母单元序列。在3400小时的Microsoft Cortana语音助手任务中进行评估后，与我们提出的关注CTC相结合时，最终的声 - 词解决方案将基线词CTC的相对误差率（WER）降低了12.09％。不使用任何语言模型（LM）或复合解码器的这种E2E模型胜过具有强的LM和解码器的传统的与上下文相关的音素CTC，其相对6.79％。

##### URL
[https://arxiv.org/abs/1803.05566](https://arxiv.org/abs/1803.05566)

##### PDF
[https://arxiv.org/pdf/1803.05566](https://arxiv.org/pdf/1803.05566)

