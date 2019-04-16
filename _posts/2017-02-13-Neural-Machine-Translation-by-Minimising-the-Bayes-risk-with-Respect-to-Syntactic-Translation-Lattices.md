---
layout: post
title: "Neural Machine Translation by Minimising the Bayes-risk with Respect to Syntactic Translation Lattices"
date: 2017-02-13 14:29:34
categories: arXiv_CL
tags: arXiv_CL NMT
author: Felix Stahlberg, Adrià de Gispert, Eva Hasler, Bill Byrne
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel scheme to combine neural machine translation (NMT) with traditional statistical machine translation (SMT). Our approach borrows ideas from linearised lattice minimum Bayes-risk decoding for SMT. The NMT score is combined with the Bayes-risk of the translation according the SMT lattice. This makes our approach much more flexible than $n$-best list or lattice rescoring as the neural decoder is not restricted to the SMT search space. We show an efficient and simple way to integrate risk estimation into the NMT decoder which is suitable for word-level as well as subword-unit-level NMT. We test our method on English-German and Japanese-English and report significant gains over lattice rescoring on several data sets for both single and ensembled NMT. The MBR decoder produces entirely new hypotheses far beyond simply rescoring the SMT search space or fixing UNKs in the NMT output.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1612.03791](https://arxiv.org/abs/1612.03791)

##### PDF
[https://arxiv.org/pdf/1612.03791](https://arxiv.org/pdf/1612.03791)

