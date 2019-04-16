---
layout: post
title: "Improving Character-based Decoding Using Target-Side Morphological Information for Neural Machine Translation"
date: 2018-04-17 23:54:26
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Peyman Passban, Qun Liu, Andy Way
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, neural machine translation (NMT) has emerged as a powerful alternative to conventional statistical approaches. However, its performance drops considerably in the presence of morphologically rich languages (MRLs). Neural engines usually fail to tackle the large vocabulary and high out-of-vocabulary (OOV) word rate of MRLs. Therefore, it is not suitable to exploit existing word-based models to translate this set of languages. In this paper, we propose an extension to the state-of-the-art model of Chung et al. (2016), which works at the character level and boosts the decoder with target-side morphological information. In our architecture, an additional morphology table is plugged into the model. Each time the decoder samples from a target vocabulary, the table sends auxiliary signals from the most relevant affixes in order to enrich the decoder's current state and constrain it to provide better predictions. We evaluated our model to translate English into German, Russian, and Turkish as three MRLs and observed significant improvements.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.06506](https://arxiv.org/abs/1804.06506)

##### PDF
[https://arxiv.org/pdf/1804.06506](https://arxiv.org/pdf/1804.06506)

