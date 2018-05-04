---
layout: post
title: "Investigating Backtranslation in Neural Machine Translation"
date: 2018-04-17 12:16:25
categories: arXiv_CL
tags: arXiv_CL NMT
author: Alberto Poncelas, Dimitar Shterionov, Andy Way, Gideon Maillette de Buy Wenniger, Peyman Passban
mathjax: true
---

* content
{:toc}

##### Abstract
A prerequisite for training corpus-based machine translation (MT) systems -- either Statistical MT (SMT) or Neural MT (NMT) -- is the availability of high-quality parallel data. This is arguably more important today than ever before, as NMT has been shown in many studies to outperform SMT, but mostly when large parallel corpora are available; in cases where data is limited, SMT can still outperform NMT. Recently researchers have shown that back-translating monolingual data can be used to create synthetic parallel corpora, which in turn can be used in combination with authentic parallel data to train a high-quality NMT system. Given that large collections of new parallel text become available only quite rarely, backtranslation has become the norm when building state-of-the-art NMT systems, especially in resource-poor scenarios. However, we assert that there are many unknown factors regarding the actual effects of back-translated data on the translation capabilities of an NMT model. Accordingly, in this work we investigate how using back-translated data as a training corpus -- both as a separate standalone dataset as well as combined with human-generated parallel data -- affects the performance of an NMT model. We use incrementally larger amounts of back-translated data to train a range of NMT systems for German-to-English, and analyse the resulting translation performance.

##### Abstract (translated by Google)
训练基于语料库的机器翻译（MT）系统（统计MT（SMT）或神经MT（NMT））的先决条件是提供高质量的并行数据。这可以说比以往任何时候都更重要，因为NMT已经在许多研究中表现出超越SMT，但主要是在大型平行语料库可用时;在数据有限的情况下，SMT仍然可以胜过NMT。最近研究人员已经表明，反向翻译单语言数据可以用来创建合成的平行语料库，这反过来又可以与真实的并行数据结合使用来训练高质量的NMT系统。鉴于大量新的并行文本很少可用，所以在构建最先进的NMT系统时，回传已成为常态，特别是在资源匮乏的情况下。然而，我们断言，关于NMT模型的翻译能力的背面翻译数据的实际影响存在许多未知因素。因此，在这项工作中，我们研究如何使用回译数据作为训练语料库 - 既作为单独的独立数据集，也结合人类生成的并行数据 - 影响NMT模型的性能。我们逐渐使用大量的回译数据来训练一系列德语到英语的NMT系统，并分析翻译结果。

##### URL
[https://arxiv.org/abs/1804.06189](https://arxiv.org/abs/1804.06189)

##### PDF
[https://arxiv.org/pdf/1804.06189](https://arxiv.org/pdf/1804.06189)

