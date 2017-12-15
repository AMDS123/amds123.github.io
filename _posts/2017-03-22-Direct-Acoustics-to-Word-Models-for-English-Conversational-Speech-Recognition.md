---
layout: post
title: "Direct Acoustics-to-Word Models for English Conversational Speech Recognition"
date: 2017-03-22 17:17:16
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Classification Language_Model Recognition
author: Kartik Audhkhasi, Bhuvana Ramabhadran, George Saon, Michael Picheny, David Nahamoo
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work on end-to-end automatic speech recognition (ASR) has shown that the connectionist temporal classification (CTC) loss can be used to convert acoustics to phone or character sequences. Such systems are used with a dictionary and separately-trained Language Model (LM) to produce word sequences. However, they are not truly end-to-end in the sense of mapping acoustics directly to words without an intermediate phone representation. In this paper, we present the first results employing direct acoustics-to-word CTC models on two well-known public benchmark tasks: Switchboard and CallHome. These models do not require an LM or even a decoder at run-time and hence recognize speech with minimal complexity. However, due to the large number of word output units, CTC word models require orders of magnitude more data to train reliably compared to traditional systems. We present some techniques to mitigate this issue. Our CTC word model achieves a word error rate of 13.0%/18.8% on the Hub5-2000 Switchboard/CallHome test sets without any LM or decoder compared with 9.6%/16.0% for phone-based CTC with a 4-gram LM. We also present rescoring results on CTC word model lattices to quantify the performance benefits of a LM, and contrast the performance of word and phone CTC models.

##### Abstract (translated by Google)
端到端自动语音识别（ASR）最近的工作表明，连接主义时态分类（CTC）丢失可用于将声学转换为手机或字符序列。这样的系统与字典和单独训练的语言模型（LM）一起使用来产生单词序列。然而，在没有中间电话代表的情况下将声学直接映射到词语的意义上，它们并不是真正的端对端。在本文中，我们介绍了在两个着名的公共基准测试任务中使用直接声学到字CTC模型的第一个结果：交换机和CallHome。这些模型在运行时不需要LM或甚至解码器，因此以最小的复杂度来识别语音。然而，由于大量的字输出单元，与传统系统相比，CTC字模型需要更多数量的数据来可靠地训练。我们提出一些技巧来缓解这个问题。在没有任何LM或解码器的Hub5-2000交换机/ CallHome测试仪中，我们的CTC字模型实现了13.0％/ 18.8％的字错误率，而具有4-gram LM的基于电话的CTC的话错误率为9.6％/ 16.0％。我们还在CTC字模型格上提出重新评分结果来量化LM的性能优势，并对比字和电话CTC模型的性能。

##### URL
[https://arxiv.org/abs/1703.07754](https://arxiv.org/abs/1703.07754)

##### PDF
[https://arxiv.org/pdf/1703.07754](https://arxiv.org/pdf/1703.07754)

