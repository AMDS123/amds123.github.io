---
layout: post
title: "EAT2seq: A generic framework for controlled sentence transformation without task-specific training"
date: 2019-03-15 14:04:34
categories: arXiv_CL
tags: arXiv_CL Text_Generation Style_Transfer
author: Tommo Gr&#xf6;ndahl, N. Asokan
mathjax: true
---

* content
{:toc}

##### Abstract
We present EAT2seq: a novel method to architect automatic linguistic transformations for a number of tasks, including controlled grammatical or lexical changes, style transfer, text generation, and machine translation. Our approach consists in creating an abstract representation of a sentence's meaning and grammar, which we use as input to an encoder-decoder network trained to reproduce the original sentence. Manipulating the abstract representation allows the transformation of sentences according to user-provided parameters, both grammatically and lexically, in any combination. The same architecture can further be used for controlled text generation, and has additional promise for machine translation. This strategy holds the promise of enabling many tasks that were hitherto outside the scope of NLP techniques for want of sufficient training data. We provide empirical evidence for the effectiveness of our approach by reproducing and transforming English sentences, and evaluating the results both manually and automatically. A single model trained on monolingual data is used for all tasks without any task-specific training. For a model trained on 8.5 million sentences, we report a BLEU score of 74.45 for reproduction, and scores between 55.29 and 81.82 for back-and-forth grammatical transformations across 14 category pairs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09381](http://arxiv.org/abs/1902.09381)

##### PDF
[http://arxiv.org/pdf/1902.09381](http://arxiv.org/pdf/1902.09381)

