---
layout: post
title: "Evaluating Discourse Phenomena in Neural Machine Translation"
date: 2018-04-20 12:05:27
categories: arXiv_CL
tags: arXiv_CL NMT
author: Rachel Bawden, Rico Sennrich, Alexandra Birch, Barry Haddow
mathjax: true
---

* content
{:toc}

##### Abstract
For machine translation to tackle discourse phenomena, models must have access to extra-sentential linguistic context. There has been recent interest in modelling context in neural machine translation (NMT), but models have been principally evaluated with standard automatic metrics, poorly adapted to evaluating discourse phenomena. In this article, we present hand-crafted, discourse test sets, designed to test the models' ability to exploit previous source and target sentences. We investigate the performance of recently proposed multi-encoder NMT models trained on subtitles for English to French. We also explore a novel way of exploiting context from the previous sentence. Despite gains using BLEU, multi-encoder models give limited improvement in the handling of discourse phenomena: 50% accuracy on our coreference test set and 53.5% for coherence/cohesion (compared to a non-contextual baseline of 50%). A simple strategy of decoding the concatenation of the previous and current sentence leads to good performance, and our novel strategy of multi-encoding and decoding of two sentences leads to the best performance (72.5% for coreference and 57% for coherence/cohesion), highlighting the importance of target-side context.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.00513](https://arxiv.org/abs/1711.00513)

##### PDF
[https://arxiv.org/pdf/1711.00513](https://arxiv.org/pdf/1711.00513)

