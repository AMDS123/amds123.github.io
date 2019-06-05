---
layout: post
title: "Toward Grammatical Error Detection from Sentence Labels: Zero-shot Sequence Labeling with CNNs and Contextualized Embeddings"
date: 2019-06-04 01:54:42
categories: arXiv_CL
tags: arXiv_CL Attention Embedding RNN Detection
author: Allen Schmaltz
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot grammatical error detection is the task of tagging token-level errors in a sentence when only given access to labels at the sentence-level for training. Recent work has explored attention- and gradient-based approaches for the task. We extend this line of research to CNNs by analyzing a straightforward decomposition of the sentence-level classifier. Without modification to the underlying architecture, a single-layer CNN can be used to achieve similar F1 scores to a bi-LSTM attention-based approach specifically modified for the task of zero-shot labeling on the standard dataset, as a result of relatively strong recall, but weaker precision. Interestingly, with the advantage of pre-trained contextualized embeddings, this approach yields competitive F1 scores (and with a limited amount of token-labeled data for tuning, F0.5 scores) with baseline (but no longer state-of-the-art) fully supervised bi-LSTM models (using standard pre-trained word embeddings), despite only having access to sentence-level labels for training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01154](http://arxiv.org/abs/1906.01154)

##### PDF
[http://arxiv.org/pdf/1906.01154](http://arxiv.org/pdf/1906.01154)

