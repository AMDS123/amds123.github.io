---
layout: post
title: "Semi-Autoregressive Neural Machine Translation"
date: 2018-08-26 16:22:30
categories: arXiv_CL
tags: arXiv_CL
author: Chunqi Wang, Ji Zhang, Haiqing Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Existing approaches to neural machine translation are typically autoregressive models. While these models attain state-of-the-art translation quality, they are suffering from low parallelizability and thus slow at decoding long sequences. In this paper, we propose a novel model for fast sequence generation --- the semi-autoregressive Transformer (SAT). The SAT keeps the autoregressive property in global but relieves in local and thus are able to produce multiple successive words in parallel at each time step. Experiments conducted on English-German and Chinese-English translation tasks show that the SAT achieves a good balance between translation quality and decoding speed. On WMT'14 English-German translation, the SAT achieves 5.58$\times$ speedup while maintaining 88\% translation quality, significantly better than the previous non-autoregressive methods. When produces two words at each time step, the SAT is almost lossless (only 1\% degeneration in BLEU score).

##### Abstract (translated by Google)
现有的神经机器翻译方法通常是自回归模型。虽然这些模型获得了最先进的翻译质量，但它们具有低并行性，因此在解码长序列时变慢。在本文中，我们提出了一种新的快速序列生成模型 - 半自回归变换器（SAT）。 SAT将自回归属性保持在全局但在本地缓解，因此能够在每个时间步骤并行生成多个连续的单词。在英语 - 德语和汉英翻译任务上进行的实验表明，SAT在翻译质量和解码速度之间实现了良好的平衡。在WMT'14英语 - 德语翻译中，SAT达到5.58 $ \次加速，同时保持88％的翻译质量，明显优于以前的非自回归方法。当在每个时间步产生两个单词时，SAT几乎是无损的（BLEU得分中只有1％的变性）。

##### URL
[http://arxiv.org/abs/1808.08583](http://arxiv.org/abs/1808.08583)

##### PDF
[http://arxiv.org/pdf/1808.08583](http://arxiv.org/pdf/1808.08583)

