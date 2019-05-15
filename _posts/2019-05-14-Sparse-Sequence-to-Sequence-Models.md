---
layout: post
title: "Sparse Sequence-to-Sequence Models"
date: 2019-05-14 16:21:34
categories: arXiv_CL
tags: arXiv_CL Sparse Attention
author: Ben Peters, Vlad Niculae, André F.T. Martins
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models are a powerful workhorse of NLP. Most variants employ a softmax transformation in both their attention mechanism and output layer, leading to dense alignments and strictly positive output probabilities. This density is wasteful, making models less interpretable and assigning probability mass to many implausible outputs. In this paper, we propose sparse sequence-to-sequence models, rooted in a new family of $\alpha$-entmax transformations, which includes softmax and sparsemax as particular cases, and is sparse for any $\alpha > 1$. We provide fast algorithms to evaluate these transformations and their gradients, which scale well for large vocabulary sizes. Our models are able to produce sparse alignments and to assign nonzero probability to a short list of plausible outputs, sometimes rendering beam search exact. Experiments on morphological inflection and machine translation reveal consistent gains over dense models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05702](https://arxiv.org/abs/1905.05702)

##### PDF
[https://arxiv.org/pdf/1905.05702](https://arxiv.org/pdf/1905.05702)

