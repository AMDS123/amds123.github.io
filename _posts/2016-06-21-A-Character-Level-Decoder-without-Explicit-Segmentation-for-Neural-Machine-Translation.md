---
layout: post
title: "A Character-Level Decoder without Explicit Segmentation for Neural Machine Translation"
date: 2016-06-21 01:12:22
categories: arXiv_SD
tags: arXiv_SD Segmentation Attention
author: Junyoung Chung, Kyunghyun Cho, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
The existing machine translation systems, whether phrase-based or neural, have relied almost exclusively on word-level modelling with explicit segmentation. In this paper, we ask a fundamental question: can neural machine translation generate a character sequence without any explicit segmentation? To answer this question, we evaluate an attention-based encoder-decoder with a subword-level encoder and a character-level decoder on four language pairs--En-Cs, En-De, En-Ru and En-Fi-- using the parallel corpora from WMT'15. Our experiments show that the models with a character-level decoder outperform the ones with a subword-level decoder on all of the four language pairs. Furthermore, the ensembles of neural models with a character-level decoder outperform the state-of-the-art non-neural machine translation systems on En-Cs, En-De and En-Fi and perform comparably on En-Ru.

##### Abstract (translated by Google)
现有的机器翻译系统，无论是基于短语的还是神经的，都几乎完全依赖于具有明确分割的字级建模。在本文中，我们提出一个基本问题：神经机器翻译能否生成一个字符序列而不需要任何明确的分割？为了回答这个问题，我们使用四个语言对（En-Cs，En-De，En-Ru和En-Fi），使用子字级编码器和字符级解码器评估基于注意力的编码器 - 解码器来自WMT'15的平行语料库。我们的实验显示，在所有四种语言对中，具有字符级解码器的模型的性能优于具有子字级解码器的模型。此外，具有字符级解码器的神经模型的集合胜过En-Cs，En-De和En-Fi中的最先进的非神经机器翻译系统，并且在En-Ru上执行相同的操作。

##### URL
[https://arxiv.org/abs/1603.06147](https://arxiv.org/abs/1603.06147)

##### PDF
[https://arxiv.org/pdf/1603.06147](https://arxiv.org/pdf/1603.06147)

