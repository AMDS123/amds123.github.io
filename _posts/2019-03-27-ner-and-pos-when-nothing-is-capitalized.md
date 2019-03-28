---
layout: post
title: "ner and pos when nothing is capitalized"
date: 2019-03-27 01:57:18
categories: arXiv_CL
tags: arXiv_CL Detection Recognition
author: Stephen Mayhew, Tatiana Tsygankova, Dan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
For those languages which use it, capitalization is an important signal for the fundamental NLP tasks of Named Entity Recognition (NER) and Part of Speech (POS) tagging. In fact, it is such a strong signal that model performance on these tasks drops sharply in common lowercased scenarios, such as noisy web text or machine translation outputs. In this work, we perform a systematic analysis of solutions to this problem, modifying only the casing of the train or test data using lowercasing and truecasing methods. While prior work and first impressions might suggest training a caseless model, or using a truecaser at test time, we show that the most effective strategy is a concatenation of cased and lowercased training data, producing a single model with high performance on both cased and uncased text. As shown in our experiments, this result holds across tasks and input representations. Finally, we show that our proposed solution gives an 8% F1 improvement in mention detection on noisy out-of-domain Twitter data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11222](http://arxiv.org/abs/1903.11222)

##### PDF
[http://arxiv.org/pdf/1903.11222](http://arxiv.org/pdf/1903.11222)

