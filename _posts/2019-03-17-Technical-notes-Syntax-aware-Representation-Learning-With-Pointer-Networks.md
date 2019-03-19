---
layout: post
title: "Technical notes: Syntax-aware Representation Learning With Pointer Networks"
date: 2019-03-17 20:26:56
categories: arXiv_CL
tags: arXiv_CL Knowledge Represenation_Learning RNN
author: Matteo Grella
mathjax: true
---

* content
{:toc}

##### Abstract
This is a work-in-progress report, which aims to share preliminary results of a novel sequence-to-sequence schema for dependency parsing that relies on a combination of a BiLSTM and two Pointer Networks (Vinyals et al., 2015), in which the final softmax function has been replaced with the logistic regression. The two pointer networks co-operate to develop a latent syntactic knowledge, by learning the lexical properties of "selection" and the lexical properties of "selectability", respectively. At the moment and without fine-tuning, the parser implementation gets a UAS of 93.14% on the English Penn-treebank (Marcus et al., 1993) annotated with Stanford Dependencies: 2-3% under the SOTA but yet attractive as a baseline of the approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07161](http://arxiv.org/abs/1903.07161)

##### PDF
[http://arxiv.org/pdf/1903.07161](http://arxiv.org/pdf/1903.07161)

