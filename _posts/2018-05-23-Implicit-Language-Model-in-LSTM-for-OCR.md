---
layout: post
title: "Implicit Language Model in LSTM for OCR"
date: 2018-05-23 22:01:38
categories: arXiv_CV
tags: arXiv_CV OCR RNN Language_Model
author: Ekraam Sabir, Stephen Rawls, Prem Natarajan
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks have become the technique of choice for OCR, but many aspects of how and why they deliver superior performance are still unknown. One key difference between current neural network techniques using LSTMs and the previous state-of-the-art HMM systems is that HMM systems have a strong independence assumption. In comparison LSTMs have no explicit constraints on the amount of context that can be considered during decoding. In this paper we show that they learn an implicit LM and attempt to characterize the strength of the LM in terms of equivalent n-gram context. We show that this implicitly learned language model provides a 2.4\% CER improvement on our synthetic test set when compared against a test set of random characters (i.e. not naturally occurring sequences), and that the LSTM learns to use up to 5 characters of context (which is roughly 88 frames in our configuration). We believe that this is the first ever attempt at characterizing the strength of the implicit LM in LSTM based OCR systems.

##### Abstract (translated by Google)
神经网络已成为OCR的首选技术，但其如何以及为何提供卓越性能的许多方面仍未知。目前使用LSTM的神经网络技术和先前的最先进的HMM系统之间的一个关键区别在于HMM系统具有强大的独立性假设。相比之下，LSTM对解码期间可以考虑的上下文的数量没有明确的限制。在本文中，我们表明他们学习了一个隐式的LM，并尝试用等价的n元语境描述LM的强度。我们证明，当与一组随机字符测试集（即不是自然发生的序列）进行比较时，这种隐含学习的语言模型在我们的综合测试集上提供了2.4％的CER改进，并且LSTM学习使用多达5个字符的上下文（这在我们的配置中大约为88帧）。我们相信这是有史以来第一次尝试描述基于LSTM的OCR系统中隐式LM的强度。

##### URL
[http://arxiv.org/abs/1805.09441](http://arxiv.org/abs/1805.09441)

##### PDF
[http://arxiv.org/pdf/1805.09441](http://arxiv.org/pdf/1805.09441)

