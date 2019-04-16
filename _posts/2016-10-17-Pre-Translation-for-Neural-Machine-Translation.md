---
layout: post
title: "Pre-Translation for Neural Machine Translation"
date: 2016-10-17 18:14:24
categories: arXiv_CL
tags: arXiv_CL NMT
author: Jan Niehues, Eunah Cho, Thanh-Le Ha, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the development of neural machine translation (NMT) has significantly improved the translation quality of automatic machine translation. While most sentences are more accurate and fluent than translations by statistical machine translation (SMT)-based systems, in some cases, the NMT system produces translations that have a completely different meaning. This is especially the case when rare words occur. When using statistical machine translation, it has already been shown that significant gains can be achieved by simplifying the input in a preprocessing step. A commonly used example is the pre-reordering approach. In this work, we used phrase-based machine translation to pre-translate the input into the target language. Then a neural machine translation system generates the final hypothesis using the pre-translation. Thereby, we use either only the output of the phrase-based machine translation (PBMT) system or a combination of the PBMT output and the source sentence. We evaluate the technique on the English to German translation task. Using this approach we are able to outperform the PBMT system as well as the baseline neural MT system by up to 2 BLEU points. We analyzed the influence of the quality of the initial system on the final result.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1610.05243](https://arxiv.org/abs/1610.05243)

##### PDF
[https://arxiv.org/pdf/1610.05243](https://arxiv.org/pdf/1610.05243)

