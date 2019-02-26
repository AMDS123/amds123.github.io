---
layout: post
title: "Using logical form encodings for unsupervised linguistic transformation: Theory and applications"
date: 2019-02-25 15:49:10
categories: arXiv_CL
tags: arXiv_CL Text_Generation Style_Transfer
author: Tommo Gr&#xf6;ndahl, N. Asokan
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method to architect automatic linguistic transformations for a number of tasks, including controlled grammatical or lexical changes, style transfer, text generation, and machine translation. Our approach consists in creating an abstract representation of a sentence's meaning and grammar, which we use as input to an encoder-decoder network trained to reproduce the original sentence. Manipulating the abstract representation allows the transformation of sentences according to user-provided parameters, both grammatically and lexically, in any combination. Additionally, the same architecture can be used for controlled text generation, and even unsupervised machine translation, where the network is used to translate between different languages using no parallel corpora outside of a lemma-level dictionary. This strategy holds the promise of enabling many tasks that were hitherto outside the scope of NLP techniques for want of sufficient training data. We provide empirical evidence for the effectiveness of our approach by reproducing and transforming English sentences, and evaluating the results both manually and automatically. A single unsupervised model is used for all tasks. We report BLEU scores between 55.29 and 81.82 for sentence reproduction as well as back-and-forth grammatical transformations between 14 class pairs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09381](http://arxiv.org/abs/1902.09381)

##### PDF
[http://arxiv.org/pdf/1902.09381](http://arxiv.org/pdf/1902.09381)

