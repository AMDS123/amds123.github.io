---
layout: post
title: "Unsupervised Pretraining for Sequence to Sequence Learning"
date: 2018-02-22 01:57:27
categories: arXiv_CL
tags: arXiv_CL Summarization Language_Model
author: Prajit Ramachandran, Peter J. Liu, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a general unsupervised learning method to improve the accuracy of sequence to sequence (seq2seq) models. In our method, the weights of the encoder and decoder of a seq2seq model are initialized with the pretrained weights of two language models and then fine-tuned with labeled data. We apply this method to challenging benchmarks in machine translation and abstractive summarization and find that it significantly improves the subsequent supervised models. Our main result is that pretraining improves the generalization of seq2seq models. We achieve state-of-the art results on the WMT English$\rightarrow$German task, surpassing a range of methods using both phrase-based machine translation and neural machine translation. Our method achieves a significant improvement of 1.3 BLEU from the previous best models on both WMT'14 and WMT'15 English$\rightarrow$German. We also conduct human evaluations on abstractive summarization and find that our method outperforms a purely supervised learning baseline in a statistically significant manner.

##### Abstract (translated by Google)
这项工作提出了一种通用的无监督学习方法来提高序列（seq2seq）模型的准确性。在我们的方法中，seq2seq模型的编码器和解码器的权重用两种语言模型的预训练权重进行初始化，然后用标记数据进行微调。我们将这种方法应用于机器翻译和抽象概括中具有挑战性的基准，并发现它显着改善了随后的监督模型。我们的主要结果是预训练改进了seq2seq模型的推广。我们在WMT英语$ \ rightarrow $德语任务中取得了最先进的成果，超越了使用基于短语的机器翻译和神经机器翻译的一系列方法。我们的方法在WMT'14和WMT'15英语版$ \ rightarrow $德语版上实现了1.3 BLEU的重大改进。我们还对抽象概括进行了人体评估，发现我们的方法在统计学意义上胜过纯粹监督学习的基线。

##### URL
[http://arxiv.org/abs/1611.02683](http://arxiv.org/abs/1611.02683)

##### PDF
[http://arxiv.org/pdf/1611.02683](http://arxiv.org/pdf/1611.02683)

