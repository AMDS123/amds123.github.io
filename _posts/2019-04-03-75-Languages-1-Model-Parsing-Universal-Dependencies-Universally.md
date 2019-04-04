---
layout: post
title: "75 Languages, 1 Model: Parsing Universal Dependencies Universally"
date: 2019-04-03 16:52:55
categories: arXiv_CL
tags: arXiv_CL Attention Prediction
author: Daniel Kondratyuk
mathjax: true
---

* content
{:toc}

##### Abstract
We present UDify, a multilingual multi-task model capable of accurately predicting universal part-of-speech, morphological features, lemmas, and dependency trees simultaneously for all 124 Universal Dependencies treebanks across 75 languages. By leveraging a multilingual BERT self-attention model pretrained on 104 languages, we found that fine-tuning it on all datasets concatenated together with simple softmax classifiers for each UD task can result in state-of-the-art UPOS, UFeats, Lemmas, UAS, and LAS scores, without requiring any recurrent or language-specific components. We evaluate UDify for multilingual learning, showing that low-resource languages benefit the most from cross-linguistic annotations. We also evaluate for zero-shot learning, with results suggesting that multilingual training provides strong UD predictions even for languages that neither UDify nor BERT have ever been trained on. Code for UDify is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02099](https://arxiv.org/abs/1904.02099)

##### PDF
[https://arxiv.org/pdf/1904.02099](https://arxiv.org/pdf/1904.02099)

