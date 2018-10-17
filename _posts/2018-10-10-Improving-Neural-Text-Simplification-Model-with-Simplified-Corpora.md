---
layout: post
title: "Improving Neural Text Simplification Model with Simplified Corpora"
date: 2018-10-10 09:14:06
categories: arXiv_CL
tags: arXiv_CL
author: Jipeng Qiang
mathjax: true
---

* content
{:toc}

##### Abstract
Text simplification (TS) can be viewed as monolingual translation task, translating between text variations within a single language. Recent neural TS models draw on insights from neural machine translation to learn lexical simplification and content reduction using encoder-decoder model. But different from neural machine translation, we cannot obtain enough ordinary and simplified sentence pairs for TS, which are expensive and time-consuming to build. Target-side simplified sentences plays an important role in boosting fluency for statistical TS, and we investigate the use of simplified sentences to train, with no changes to the network architecture. We propose to pair simple training sentence with a synthetic ordinary sentence via back-translation, and treating this synthetic data as additional training data. We train encoder-decoder model using synthetic sentence pairs and original sentence pairs, which can obtain substantial improvements on the available WikiLarge data and WikiSmall data compared with the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04428](https://arxiv.org/abs/1810.04428)

##### PDF
[https://arxiv.org/pdf/1810.04428](https://arxiv.org/pdf/1810.04428)

