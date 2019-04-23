---
layout: post
title: "Gradient-based Inference for Networks with Output Constraints"
date: 2019-04-22 15:24:11
categories: arXiv_CL
tags: arXiv_CL Inference Prediction
author: Jay Yoon Lee, Sanket Vaibhav Mehta, Michael Wick, Jean-Baptiste Tristan, Jaime Carbonell
mathjax: true
---

* content
{:toc}

##### Abstract
Practitioners apply neural networks to increasingly complex problems in natural language processing, such as syntactic parsing and semantic role labeling that have rich output structures. Many such structured-prediction problems require deterministic constraints on the output values; for example, in sequence-to-sequence syntactic parsing, we require that the sequential outputs encode valid trees. While hidden units might capture such properties, the network is not always able to learn such constraints from the training data alone, and practitioners must then resort to post-processing. In this paper, we present an inference method for neural networks that enforces deterministic constraints on outputs without performing rule-based post-processing or expensive discrete search. Instead, in the spirit of gradient-based training, we enforce constraints with gradient-based inference (GBI): for each input at test-time, we nudge continuous model weights until the network's unconstrained inference procedure generates an output that satisfies the constraints. We study the efficacy of GBI on three tasks with hard constraints: semantic role labeling, syntactic parsing, and sequence transduction. In each case, the algorithm not only satisfies constraints but improves accuracy, even when the underlying network is state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1707.08608](http://arxiv.org/abs/1707.08608)

##### PDF
[http://arxiv.org/pdf/1707.08608](http://arxiv.org/pdf/1707.08608)

