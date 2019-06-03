---
layout: post
title: "A Lightweight Recurrent Network for Sequence Modeling"
date: 2019-05-30 21:40:46
categories: arXiv_CL
tags: arXiv_CL Attention
author: Biao Zhang, Rico Sennrich
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent networks have achieved great success on various sequential tasks with the assistance of complex recurrent units, but suffer from severe computational inefficiency due to weak parallelization. One direction to alleviate this issue is to shift heavy computations outside the recurrence. In this paper, we propose a lightweight recurrent network, or LRN. LRN uses input and forget gates to handle long-range dependencies as well as gradient vanishing and explosion, with all parameter related calculations factored outside the recurrence. The recurrence in LRN only manipulates the weight assigned to each token, tightly connecting LRN with self-attention networks. We apply LRN as a drop-in replacement of existing recurrent units in several neural sequential models. Extensive experiments on six NLP tasks show that LRN yields the best running efficiency with little or no loss in model performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13324](http://arxiv.org/abs/1905.13324)

##### PDF
[http://arxiv.org/pdf/1905.13324](http://arxiv.org/pdf/1905.13324)

