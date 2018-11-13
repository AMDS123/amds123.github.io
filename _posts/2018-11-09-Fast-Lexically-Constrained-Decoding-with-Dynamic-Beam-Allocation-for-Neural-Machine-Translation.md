---
layout: post
title: "Fast Lexically Constrained Decoding with Dynamic Beam Allocation for Neural Machine Translation"
date: 2018-11-09 21:40:15
categories: arXiv_CL
tags: arXiv_CL NMT Relation
author: Matt Post, David Vilar
mathjax: true
---

* content
{:toc}

##### Abstract
The end-to-end nature of neural machine translation (NMT) removes many ways of manually guiding the translation process that were available in older paradigms. Recent work, however, has introduced a new capability: lexically constrained or guided decoding, a modification to beam search that forces the inclusion of pre-specified words and phrases in the output. However, while theoretically sound, existing approaches have computational complexities that are either linear (Hokamp and Liu, 2017) or exponential (Anderson et al., 2017) in the number of constraints. We present a algorithm for lexically constrained decoding with a complexity of O(1) in the number of constraints. We demonstrate the algorithms remarkable ability to properly place these constraints, and use it to explore the shaky relationship between model and BLEU scores. Our implementation is available as part of Sockeye.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.06609](http://arxiv.org/abs/1804.06609)

##### PDF
[http://arxiv.org/pdf/1804.06609](http://arxiv.org/pdf/1804.06609)

