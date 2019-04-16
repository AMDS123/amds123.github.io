---
layout: post
title: "Correcting Length Bias in Neural Machine Translation"
date: 2018-08-31 21:59:35
categories: arXiv_CL
tags: arXiv_CL NMT
author: Kenton Murray, David Chiang
mathjax: true
---

* content
{:toc}

##### Abstract
We study two problems in neural machine translation (NMT). First, in beam search, whereas a wider beam should in principle help translation, it often hurts NMT. Second, NMT has a tendency to produce translations that are too short. Here, we argue that these problems are closely related and both rooted in label bias. We show that correcting the brevity problem almost eliminates the beam problem; we compare some commonly-used methods for doing this, finding that a simple per-word reward works well; and we introduce a simple and quick way to tune this reward using the perceptron algorithm.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.10006](https://arxiv.org/abs/1808.10006)

##### PDF
[https://arxiv.org/pdf/1808.10006](https://arxiv.org/pdf/1808.10006)

