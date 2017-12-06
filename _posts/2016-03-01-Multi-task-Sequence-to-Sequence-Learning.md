---
layout: post
title: 'Multi-task Sequence to Sequence Learning'
date: 2016-03-01 10:55:58
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption
author: Minh-Thang Luong, Quoc V. Le, Ilya Sutskever, Oriol Vinyals, Lukasz Kaiser
---

* content
{:toc}

##### Abstract
Sequence to sequence learning has recently emerged as a new paradigm in supervised learning. To date, most of its applications focused on only one task and not much work explored this framework for multiple tasks. This paper examines three multi-task learning (MTL) settings for sequence to sequence models: (a) the oneto-many setting - where the encoder is shared between several tasks such as machine translation and syntactic parsing, (b) the many-to-one setting - useful when only the decoder can be shared, as in the case of translation and image caption generation, and (c) the many-to-many setting - where multiple encoders and decoders are shared, which is the case with unsupervised objectives and translation. Our results show that training on a small amount of parsing and image caption data can improve the translation quality between English and German by up to 1.5 BLEU points over strong single-task baselines on the WMT benchmarks. Furthermore, we have established a new state-of-the-art result in constituent parsing with 93.0 F1. Lastly, we reveal interesting properties of the two unsupervised learning objectives, autoencoder and skip-thought, in the MTL context: autoencoder helps less in terms of perplexities but more on BLEU scores compared to skip-thought.

##### Abstract (translated by Google)
序列学习的序列最近已经成为监督学习的新范式。迄今为止，大多数应用程序只关注一个任务，并没有多少工作为多个任务探索这个框架。本文研究了序列到序列模型的三个多任务学习（MTL）设置：（a）一对多设置 - 编码器在几个任务之间共享，如机器翻译和句法分析;（b）多对多 - 一个设置 - 当翻译和图像标题生成的情况下只有解码器可以共享时是有用的;（c）多对多设置 - 在多个编码器和解码器共享的情况下，这是无监督的情况目标和翻译。我们的研究结果表明，对少量解析和图像标题数据进行培训，可以使英语和德语之间的翻译质量提高1.5个BLEU点，超过WMT基准测试强大的单任务基线。此外，我们还用93.0 F1建立了一个新的最新成果解析结果。最后，我们在MTL上下文中揭示了两个无监督学习目标（autoencoder和skip-thought）的有趣属性：自动编码器在困惑方面帮助较少，但与跳过思考相比，BLEU得分更多。

##### URL
[https://arxiv.org/abs/1511.06114](https://arxiv.org/abs/1511.06114)

