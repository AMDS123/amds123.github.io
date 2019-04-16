---
layout: post
title: "Beam Search Strategies for Neural Machine Translation"
date: 2017-06-14 01:00:18
categories: arXiv_CL
tags: arXiv_CL NMT
author: Markus Freitag, Yaser Al-Onaizan
mathjax: true
---

* content
{:toc}

##### Abstract
The basic concept in Neural Machine Translation (NMT) is to train a large Neural Network that maximizes the translation performance on a given parallel corpus. NMT is then using a simple left-to-right beam-search decoder to generate new translations that approximately maximize the trained conditional probability. The current beam search strategy generates the target sentence word by word from left-to- right while keeping a fixed amount of active candidates at each time step. First, this simple search is less adaptive as it also expands candidates whose scores are much worse than the current best. Secondly, it does not expand hypotheses if they are not within the best scoring candidates, even if their scores are close to the best one. The latter one can be avoided by increasing the beam size until no performance improvement can be observed. While you can reach better performance, this has the draw- back of a slower decoding speed. In this paper, we concentrate on speeding up the decoder by applying a more flexible beam search strategy whose candidate size may vary at each time step depending on the candidate scores. We speed up the original decoder by up to 43% for the two language pairs German-English and Chinese-English without losing any translation quality.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.01806](https://arxiv.org/abs/1702.01806)

##### PDF
[https://arxiv.org/pdf/1702.01806](https://arxiv.org/pdf/1702.01806)

