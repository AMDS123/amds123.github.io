---
layout: post
title: "Syntactically Supervised Transformers for Faster Neural Machine Translation"
date: 2019-06-06 19:16:16
categories: arXiv_CL
tags: arXiv_CL Inference
author: Nader Akoury, Kalpesh Krishna, Mohit Iyyer
mathjax: true
---

* content
{:toc}

##### Abstract
Standard decoders for neural machine translation autoregressively generate a single target token per time step, which slows inference especially for long outputs. While architectural advances such as the Transformer fully parallelize the decoder computations at training time, inference still proceeds sequentially. Recent developments in non- and semi- autoregressive decoding produce multiple tokens per time step independently of the others, which improves inference speed but deteriorates translation quality. In this work, we propose the syntactically supervised Transformer (SynST), which first autoregressively predicts a chunked parse tree before generating all of the target tokens in one shot conditioned on the predicted parse. A series of controlled experiments demonstrates that SynST decodes sentences ~ 5x faster than the baseline autoregressive Transformer while achieving higher BLEU scores than most competing methods on En-De and En-Fr datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02780](http://arxiv.org/abs/1906.02780)

##### PDF
[http://arxiv.org/pdf/1906.02780](http://arxiv.org/pdf/1906.02780)

