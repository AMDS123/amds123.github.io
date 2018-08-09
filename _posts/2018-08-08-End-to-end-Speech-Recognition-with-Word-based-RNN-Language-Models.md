---
layout: post
title: "End-to-end Speech Recognition with Word-based RNN Language Models"
date: 2018-08-08 03:05:11
categories: arXiv_AI
tags: arXiv_AI Attention Speech_Recognition RNN Language_Model Recognition
author: Takaaki Hori, Jaejin Cho, Shinji Watanabe
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates the impact of word-based RNN language models (RNN-LMs) on the performance of end-to-end automatic speech recognition (ASR). In our prior work, we have proposed a multi-level LM, in which character-based and word-based RNN-LMs are combined in hybrid CTC/attention-based ASR. Although this multi-level approach achieves significant error reduction in the Wall Street Journal (WSJ) task, two different LMs need to be trained and used for decoding, which increase the computational cost and memory usage. In this paper, we further propose a novel word-based RNN-LM, which allows us to decode with only the word-based LM, where it provides look-ahead word probabilities to predict next characters instead of the character-based LM, leading competitive accuracy with less computation compared to the multi-level LM. We demonstrate the efficacy of the word-based RNN-LMs using a larger corpus, LibriSpeech, in addition to WSJ we used in the prior work. Furthermore, we show that the proposed model achieves 5.1 %WER for WSJ Eval'92 test set when the vocabulary size is increased, which is the best WER reported for end-to-end ASR systems on this benchmark.

##### Abstract (translated by Google)
本文研究了基于单词的RNN语言模型（RNN-LM）对端到端自动语音识别（ASR）性能的影响。在我们之前的工作中，我们提出了一种多级LM，其中基于字符和基于字的RNN-LM组合在基于混合CTC /注意的ASR中。尽管这种多级方法在华尔街日报（WSJ）任务中实现了显着的误差减少，但是需要训练两个不同的LM并用于解码，这增加了计算成本和存储器使用。在本文中，我们进一步提出了一种新的基于单词的RNN-LM，它允许我们仅使用基于单词的LM进行解码，其中它提供预测单词概率来预测下一个字符而不是基于字符的LM，导致与多级LM相比，具有更低计算的竞争精度。除了我们在之前的工作中使用的WSJ之外，我们使用更大的语料库LibriSpeech证明了基于单词的RNN-LM的功效。此外，我们表明，当词汇量增加时，所提出的模型达到了WSJ Eval'92测试集的5.1％WER，这是该基准测试中针对端到端ASR系统报告的最佳WER。

##### URL
[http://arxiv.org/abs/1808.02608](http://arxiv.org/abs/1808.02608)

##### PDF
[http://arxiv.org/pdf/1808.02608](http://arxiv.org/pdf/1808.02608)

