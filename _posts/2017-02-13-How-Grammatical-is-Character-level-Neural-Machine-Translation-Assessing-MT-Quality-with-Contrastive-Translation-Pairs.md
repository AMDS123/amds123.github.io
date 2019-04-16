---
layout: post
title: "How Grammatical is Character-level Neural Machine Translation? Assessing MT Quality with Contrastive Translation Pairs"
date: 2017-02-13 09:59:05
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Rico Sennrich
mathjax: true
---

* content
{:toc}

##### Abstract
Analysing translation quality in regards to specific linguistic phenomena has historically been difficult and time-consuming. Neural machine translation has the attractive property that it can produce scores for arbitrary translations, and we propose a novel method to assess how well NMT systems model specific linguistic phenomena such as agreement over long distances, the production of novel words, and the faithful translation of polarity. The core idea is that we measure whether a reference translation is more probable under a NMT model than a contrastive translation which introduces a specific type of error. We present LingEval97, a large-scale data set of 97000 contrastive translation pairs based on the WMT English->German translation task, with errors automatically created with simple rules. We report results for a number of systems, and find that recently introduced character-level NMT systems perform better at transliteration than models with byte-pair encoding (BPE) segmentation, but perform more poorly at morphosyntactic agreement, and translating discontiguous units of meaning.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1612.04629](https://arxiv.org/abs/1612.04629)

##### PDF
[https://arxiv.org/pdf/1612.04629](https://arxiv.org/pdf/1612.04629)

