---
layout: post
title: "Transfer Learning for Low-Resource Neural Machine Translation"
date: 2016-04-08 00:16:35
categories: arXiv_CL
tags: arXiv_CL NMT
author: Barret Zoph, Deniz Yuret, Jonathan May, Kevin Knight
---

* content
{:toc}

##### Abstract
The encoder-decoder framework for neural machine translation (NMT) has been shown effective in large data scenarios, but is much less effective for low-resource languages. We present a transfer learning method that significantly improves Bleu scores across a range of low-resource languages. Our key idea is to first train a high-resource language pair (the parent model), then transfer some of the learned parameters to the low-resource pair (the child model) to initialize and constrain training. Using our transfer learning method we improve baseline NMT models by an average of 5.6 Bleu on four low-resource language pairs. Ensembling and unknown word replacement add another 2 Bleu which brings the NMT performance on low-resource machine translation close to a strong syntax based machine translation (SBMT) system, exceeding its performance on one language pair. Additionally, using the transfer learning model for re-scoring, we can improve the SBMT system by an average of 1.3 Bleu, improving the state-of-the-art on low-resource machine translation.

##### Abstract (translated by Google)
在大数据情况下，神经机器翻译（NMT）的编码器 - 解码器框架已经被证明是有效的，但是对于低资源语言而言效率低得多。我们提出了一种转移学习方法，可以显着提高各种低资源语言中的Bleu分数。我们的主要思想是首先训练一个高资源语言对（父模型），然后将一些学习参数转移到低资源对（子模型）来初始化和约束训练。使用我们的转移学习方法，我们改进了基线NMT模型，平均在四个低资源语言对上使用5.6Bluu。整合和未知的字替换增加了另外两个Bleu，它使低资源机器翻译上的NMT性能接近强大的基于语法的机器翻译（SBMT）系统，超过了它在一个语言对上的性能。此外，使用转移学习模型进行重新评分，我们可以平均改进SBMT系统1.3Bluu，从而改进低资源机器翻译的最新技术。

##### URL
[https://arxiv.org/abs/1604.02201](https://arxiv.org/abs/1604.02201)

