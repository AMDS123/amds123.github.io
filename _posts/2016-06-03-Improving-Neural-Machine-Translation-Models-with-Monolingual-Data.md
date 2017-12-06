---
layout: post
title: "Improving Neural Machine Translation Models with Monolingual Data"
date: 2016-06-03 15:09:54
categories: arXiv_CL
tags: arXiv_CL NMT
author: Rico Sennrich, Barry Haddow, Alexandra Birch
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) has obtained state-of-the art performance for several language pairs, while only using parallel data for training. Target-side monolingual data plays an important role in boosting fluency for phrase-based statistical machine translation, and we investigate the use of monolingual data for NMT. In contrast to previous work, which combines NMT models with separately trained language models, we note that encoder-decoder NMT architectures already have the capacity to learn the same information as a language model, and we explore strategies to train with monolingual data without changing the neural network architecture. By pairing monolingual training data with an automatic back-translation, we can treat it as additional parallel training data, and we obtain substantial improvements on the WMT 15 task English<->German (+2.8-3.7 BLEU), and for the low-resourced IWSLT 14 task Turkish->English (+2.1-3.4 BLEU), obtaining new state-of-the-art results. We also show that fine-tuning on in-domain monolingual and parallel data gives substantial improvements for the IWSLT 15 task English->German.

##### Abstract (translated by Google)
神经机器翻译（NMT）已经获得了几种语言对的最先进的性能，而只使用并行数据进行训练。目标侧的单语数据在提高基于短语的统计机器翻译的流畅性方面起着重要的作用，并且我们研究了单语言数据在NMT中的使用。与之前的将NMT模型与单独训练的语言模型相结合的工作相比，我们注意到编码器 - 解码器NMT架构已经具有学习与语言模型相同的信息的能力，并且我们探索了用单语数据训练而不改变神经网络架构。通过将单语训练数据与自动回译相结合，我们可以将其作为额外的并行训练数据，并且我们在WMT 15任务英语德语（+ 2.8-3.7 BLEU）资源丰富的IWSLT 14任务土耳其语 - >英语（+ 2.1-3.4 BLEU），获得新的最先进的成果。我们还表明，对域内单语和并行数据进行微调为IWSLT 15英语 - >德语任务提供了重大改进。

##### URL
[https://arxiv.org/abs/1511.06709](https://arxiv.org/abs/1511.06709)

