---
layout: post
title: "Training Data Augmentation for Context-Sensitive Neural Lemmatization Using Inflection Tables and Raw Text"
date: 2019-07-01 12:50:21
categories: arXiv_CL
tags: arXiv_CL Sparse
author: Toms Bergmanis, Sharon Goldwater
mathjax: true
---

* content
{:toc}

##### Abstract
Lemmatization aims to reduce the sparse data problem by relating the inflected forms of a word to its dictionary form. Using context can help, both for unseen and ambiguous words. Yet most context-sensitive approaches require full lemma-annotated sentences for training, which may be scarce or unavailable in low-resource languages. In addition (as shown here), in a low-resource setting, a lemmatizer can learn more from $n$ labeled examples of distinct words (types) than from $n$ (contiguous) labeled tokens, since the latter contain far fewer distinct types. To combine the efficiency of type-based learning with the benefits of context, we propose a way to train a context-sensitive lemmatizer with little or no labeled corpus data, using inflection tables from the UniMorph project and raw text examples from Wikipedia that provide sentence contexts for the unambiguous UniMorph examples. Despite these being unambiguous examples, the model successfully generalizes from them, leading to improved results (both overall, and especially on unseen words) in comparison to a baseline that does not use context.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01464](http://arxiv.org/abs/1904.01464)

##### PDF
[http://arxiv.org/pdf/1904.01464](http://arxiv.org/pdf/1904.01464)

