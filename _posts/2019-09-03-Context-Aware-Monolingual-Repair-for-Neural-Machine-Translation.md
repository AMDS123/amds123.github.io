---
layout: post
title: "Context-Aware Monolingual Repair for Neural Machine Translation"
date: 2019-09-03 18:12:36
categories: arXiv_CL
tags: arXiv_CL OCR NMT
author: Elena Voita, Rico Sennrich, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Modern sentence-level NMT systems often produce plausible translations of isolated sentences. However, when put in context, these translations may end up being inconsistent with each other. We propose a monolingual DocRepair model to correct inconsistencies between sentence-level translations. DocRepair performs automatic post-editing on a sequence of sentence-level translations, refining translations of sentences in context of each other. For training, the DocRepair model requires only monolingual document-level data in the target language. It is trained as a monolingual sequence-to-sequence model that maps inconsistent groups of sentences into consistent ones. The consistent groups come from the original training data; the inconsistent groups are obtained by sampling round-trip translations for each isolated sentence. We show that this approach successfully imitates inconsistencies we aim to fix: using contrastive evaluation, we show large improvements in the translation of several contextual phenomena in an English-Russian translation task, as well as improvements in the BLEU score. We also conduct a human evaluation and show a strong preference of the annotators to corrected translations over the baseline ones. Moreover, we analyze which discourse phenomena are hard to capture using monolingual data only.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01383](http://arxiv.org/abs/1909.01383)

##### PDF
[http://arxiv.org/pdf/1909.01383](http://arxiv.org/pdf/1909.01383)

