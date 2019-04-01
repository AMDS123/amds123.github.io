---
layout: post
title: "Character-Aware Decoder for Translation into Morphologically Rich Languages"
date: 2019-03-28 23:24:31
categories: arXiv_CL
tags: arXiv_CL Attention Embedding CNN NMT Relation
author: Adithya Renduchintala, Pamela Shapiro, Kevin Duh, Philipp Koehn
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) systems operate primarily on words (or subwords), ignoring lower-level patterns of morphology. We present a character-aware decoder designed to capture such patterns when translating into morphologically rich languages. We achieve character-awareness by augmenting both the softmax and embedding layers of an attention-based encoder-decoder model with convolutional neural networks that operate on the spelling of a word. To investigate performance on a wide variety of morphological phenomena, we translate English into $14$ typologically diverse target languages using the TED multi-target dataset. In this low-resource setting, the character-aware decoder provides consistent improvements with BLEU score gains of up to $+3.05$. In addition, we analyze the relationship between the gains obtained and properties of the target language and find evidence that our model does indeed exploit morphological patterns.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.02223](http://arxiv.org/abs/1809.02223)

##### PDF
[http://arxiv.org/pdf/1809.02223](http://arxiv.org/pdf/1809.02223)

