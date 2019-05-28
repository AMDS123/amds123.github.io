---
layout: post
title: "Levenshtein Transformer"
date: 2019-05-27 07:08:12
categories: arXiv_CL
tags: arXiv_CL Summarization
author: Jiatao Gu, Changhan Wang, Jake Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Modern neural sequence generation models are built to either generate tokens step-by-step from scratch or (iteratively) modify a sequence of tokens bounded by a fixed length. In this work, we develop Levenshtein Transformer, a new partially autoregressive model devised for more flexible and amenable sequence generation. Unlike previous approaches, the atomic operations of our model are insertion and deletion. The combination of them facilitates not only generation but also sequence refinement allowing dynamic length changes. We also propose a set of new training techniques dedicated at them, effectively exploiting one as the other's learning signal thanks to their complementary nature. Experiments applying the proposed model achieve comparable performance but much-improved efficiency on both generation (e.g. machine translation, text summarization) and refinement tasks (e.g. automatic post-editing). We further confirm the flexibility of our model by showing a Levenshtein Transformer trained by machine translation can straightforwardly be used for automatic post-editing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.11006](http://arxiv.org/abs/1905.11006)

##### PDF
[http://arxiv.org/pdf/1905.11006](http://arxiv.org/pdf/1905.11006)

