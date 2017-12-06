---
layout: post
title: "Neural Response Generation with Dynamic Vocabularies"
date: 2017-11-30 02:06:47
categories: arXiv_CL
tags: arXiv_CL
author: Yu Wu, Wei Wu, Dejian Yang, Can Xu, Zhoujun Li, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We study response generation for open domain conversation in chatbots. Existing methods assume that words in responses are generated from an identical vocabulary regardless of their inputs, which not only makes them vulnerable to generic patterns and irrelevant noise, but also causes a high cost in decoding. We propose a dynamic vocabulary sequence-to-sequence (DVS2S) model which allows each input to possess their own vocabulary in decoding. In training, vocabulary construction and response generation are jointly learned by maximizing a lower bound of the true objective with a Monte Carlo sampling method. In inference, the model dynamically allocates a small vocabulary for an input with the word prediction model, and conducts decoding only with the small vocabulary. Because of the dynamic vocabulary mechanism, DVS2S eludes many generic patterns and irrelevant words in generation, and enjoys efficient decoding at the same time. Experimental results on both automatic metrics and human annotations show that DVS2S can significantly outperform state-of-the-art methods in terms of response quality, but only requires 60% decoding time compared to the most efficient baseline.

##### Abstract (translated by Google)
我们在chatbots中研究开放域对话的响应生成。现有的方法假定不管输入的是什么词汇，词汇都是由相同的词汇产生的，这不仅使得它们容易受通用模式和无关噪声的影响，而且造成解码成本高。我们提出了一个动态的词汇序列 - 序列（DVS2S）模型，它允许每个输入在解码时拥有自己的词汇。在训练中，词汇构建和响应生成是通过最大化真实目标的下限与蒙特卡罗（Monte Carlo）抽样方法共同学习的。在推理中，模型动态地为单词预测模型的输入分配一个小词汇表，并且仅用小词汇表进行解码。由于动态的词汇机制，DVS2S避开了许多普通模式和不相关的词语，同时享受高效的解码。对自动度量和人类注释的实验结果表明，DVS2S在响应质量方面可以显着优于最先进的方法，但与最有效的基线相比，只需要60％的解码时间。

##### URL
[https://arxiv.org/abs/1711.11191](https://arxiv.org/abs/1711.11191)

