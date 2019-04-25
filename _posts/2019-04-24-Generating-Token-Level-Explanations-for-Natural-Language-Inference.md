---
layout: post
title: "Generating Token-Level Explanations for Natural Language Inference"
date: 2019-04-24 09:41:14
categories: arXiv_CL
tags: arXiv_CL Attention Inference RNN Classification Prediction Relation
author: James Thorne, Andreas Vlachos, Christos Christodoulopoulos, Arpit Mittal
mathjax: true
---

* content
{:toc}

##### Abstract
The task of Natural Language Inference (NLI) is widely modeled as supervised sentence pair classification. While there has been a lot of work recently on generating explanations of the predictions of classifiers on a single piece of text, there have been no attempts to generate explanations of classifiers operating on pairs of sentences. In this paper, we show that it is possible to generate token-level explanations for NLI without the need for training data explicitly annotated for this purpose. We use a simple LSTM architecture and evaluate both LIME and Anchor explanations for this task. We compare these to a Multiple Instance Learning (MIL) method that uses thresholded attention make token-level predictions. The approach we present in this paper is a novel extension of zero-shot single-sentence tagging to sentence pairs for NLI. We conduct our experiments on the well-studied SNLI dataset that was recently augmented with manually annotation of the tokens that explain the entailment relation. We find that our white-box MIL-based method, while orders of magnitude faster, does not reach the same accuracy as the black-box methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10717](http://arxiv.org/abs/1904.10717)

##### PDF
[http://arxiv.org/pdf/1904.10717](http://arxiv.org/pdf/1904.10717)

