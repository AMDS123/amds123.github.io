---
layout: post
title: "Source Traces for Temporal Difference Learning"
date: 2019-02-08 01:21:17
categories: arXiv_AI
tags: arXiv_AI
author: Silviu Pitis
mathjax: true
---

* content
{:toc}

##### Abstract
This paper motivates and develops source traces for temporal difference (TD) learning in the tabular setting. Source traces are like eligibility traces, but model potential histories rather than immediate ones. This allows TD errors to be propagated to potential causal states and leads to faster generalization. Source traces can be thought of as the model-based, backward view of successor representations (SR), and share many of the same benefits. This view, however, suggests several new ideas. First, a TD($\lambda$)-like source learning algorithm is proposed and its convergence is proven. Then, a novel algorithm for learning the source map (or SR matrix) is developed and shown to outperform the previous algorithm. Finally, various approaches to using the source/SR model are explored, and it is shown that source traces can be effectively combined with other model-based methods like Dyna and experience replay.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02907](http://arxiv.org/abs/1902.02907)

##### PDF
[http://arxiv.org/pdf/1902.02907](http://arxiv.org/pdf/1902.02907)

