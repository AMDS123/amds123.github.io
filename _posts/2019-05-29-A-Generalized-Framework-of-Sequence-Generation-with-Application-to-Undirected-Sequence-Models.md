---
layout: post
title: "A Generalized Framework of Sequence Generation with Application to Undirected Sequence Models"
date: 2019-05-29 23:47:17
categories: arXiv_CL
tags: arXiv_CL Attention Inference
author: Elman Mansimov, Alex Wang, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Undirected neural sequence models such as BERT have received renewed interest due to their success on discriminative natural language understanding tasks such as question-answering and natural language inference. The problem of generating sequences directly from these models has received relatively little attention, in part because generating from such models departs significantly from the conventional approach of monotonic generation in directed sequence models. We investigate this problem by first proposing a generalized model of sequence generation that unifies decoding in directed and undirected models. The proposed framework models the process of generation rather than a resulting sequence, and under this framework, we derive various neural sequence models as special cases, such as autoregressive, semi-autoregressive, and refinement-based non-autoregressive models. This unification enables us to adapt decoding algorithms originally developed for directed sequence models to undirected models. We demonstrate this by evaluating various decoding strategies for the recently proposed cross-lingual masked translation model. Our experiments reveal that generation from undirected sequence models, under our framework, is competitive against the state of the art on WMT'14 English-German translation. We furthermore observe that the proposed approach enables constant-time translation while losing only 1 BLEU score compared to linear-time translation from the same undirected neural sequence model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12790](http://arxiv.org/abs/1905.12790)

##### PDF
[http://arxiv.org/pdf/1905.12790](http://arxiv.org/pdf/1905.12790)

