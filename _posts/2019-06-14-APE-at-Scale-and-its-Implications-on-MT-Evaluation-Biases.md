---
layout: post
title: "APE at Scale and its Implications on MT Evaluation Biases"
date: 2019-06-14 17:32:34
categories: arXiv_CL
tags: arXiv_CL NMT
author: Markus Freitag, Isaac Caswell, Scott Roy
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we train an Automatic Post-Editing (APE) model and use it to reveal biases in standard Machine Translation (MT) evaluation procedures. The goal of our APE model is to correct typical errors introduced by the translation process, and convert the "translationese" output into natural text. Our APE model is trained entirely on monolingual data that has been round-trip translated through English, to mimic errors that are similar to the ones introduced by NMT. We apply our model to the output of existing NMT systems, and demonstrate that, while the human-judged quality improves in all cases, BLEU scores drop with forward-translated test sets. We verify these results for the WMT18 English to German, WMT15 English to French, and WMT16 English to Romanian tasks. Furthermore, we selectively apply our APE model on the output of the top submissions of the most recent WMT evaluation campaigns. We see quality improvements on all tasks of up to 2.5 BLEU points.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04790](http://arxiv.org/abs/1904.04790)

##### PDF
[http://arxiv.org/pdf/1904.04790](http://arxiv.org/pdf/1904.04790)

