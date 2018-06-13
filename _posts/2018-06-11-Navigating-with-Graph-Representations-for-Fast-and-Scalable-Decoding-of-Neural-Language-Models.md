---
layout: post
title: "Navigating with Graph Representations for Fast and Scalable Decoding of Neural Language Models"
date: 2018-06-11 18:57:49
categories: arXiv_AI
tags: arXiv_AI Language_Model
author: Minjia Zhang, Xiaodong Liu, Wenhan Wang, Jianfeng Gao, Yuxiong He
mathjax: true
---

* content
{:toc}

##### Abstract
Neural language models (NLMs) have recently gained a renewed interest by achieving state-of-the-art performance across many natural language processing (NLP) tasks. However, NLMs are very computationally demanding largely due to the computational cost of the softmax layer over a large vocabulary. We observe that, in decoding of many NLP tasks, only the probabilities of the top-K hypotheses need to be calculated preciously and K is often much smaller than the vocabulary size. This paper proposes a novel softmax layer approximation algorithm, called Fast Graph Decoder (FGD), which quickly identifies, for a given context, a set of K words that are most likely to occur according to a NLM. We demonstrate that FGD reduces the decoding time by an order of magnitude while attaining close to the full softmax baseline accuracy on neural machine translation and language modeling tasks. We also prove the theoretical guarantee on the softmax approximation quality.

##### Abstract (translated by Google)
最近，神经语言模型（NLM）通过在许多自然语言处理（NLP）任务中实现最先进的性能而重新获得了兴趣。然而，NLM在计算上要求很高，主要是由于softmax层在大量词汇表上的计算成本。我们观察到，在解码许多NLP任务时，只有顶K假设的概率需要进行精确计算，而K通常远小于词汇大小。本文提出了一种称为快速图解码器（FGD）的新型softmax层近似算法，该算法可快速识别出给定上下文中最有可能根据NLM发生的一组K字。我们证明，FGD将解码时间缩短了一个数量级，同时在神经机器翻译和语言建模任务中达到了完全softmax基线精度。我们也证明了softmax逼近质量的理论保证。

##### URL
[http://arxiv.org/abs/1806.04189](http://arxiv.org/abs/1806.04189)

##### PDF
[http://arxiv.org/pdf/1806.04189](http://arxiv.org/pdf/1806.04189)

