---
layout: post
title: "Improving Neural Machine Translation Models with Monolingual Data"
date: 2016-06-03 15:09:54
categories: arXiv_CL
tags: arXiv_CL NMT Language_Model
author: Rico Sennrich, Barry Haddow, Alexandra Birch
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) has obtained state-of-the art performance for several language pairs, while only using parallel data for training. Target-side monolingual data plays an important role in boosting fluency for phrase-based statistical machine translation, and we investigate the use of monolingual data for NMT. In contrast to previous work, which combines NMT models with separately trained language models, we note that encoder-decoder NMT architectures already have the capacity to learn the same information as a language model, and we explore strategies to train with monolingual data without changing the neural network architecture. By pairing monolingual training data with an automatic back-translation, we can treat it as additional parallel training data, and we obtain substantial improvements on the WMT 15 task English<->German (+2.8-3.7 BLEU), and for the low-resourced IWSLT 14 task Turkish->English (+2.1-3.4 BLEU), obtaining new state-of-the-art results. We also show that fine-tuning on in-domain monolingual and parallel data gives substantial improvements for the IWSLT 15 task English->German.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1511.06709](https://arxiv.org/abs/1511.06709)

##### PDF
[https://arxiv.org/pdf/1511.06709](https://arxiv.org/pdf/1511.06709)

