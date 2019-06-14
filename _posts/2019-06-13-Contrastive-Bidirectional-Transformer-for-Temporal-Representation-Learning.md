---
layout: post
title: "Contrastive Bidirectional Transformer for Temporal Representation Learning"
date: 2019-06-13 15:03:52
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Represenation_Learning
author: Chen Sun, Fabien Baradel, Kevin Murphy, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at learning representations for long sequences of continuous signals. Recently, the BERT model has demonstrated the effectiveness of stacked transformers for representing sequences of discrete signals (i.e. word tokens). Inspired by its success, we adopt the stacked transformer architecture, but generalize its training objective to maximize the mutual information between the masked signals, and the bidirectional context, via contrastive loss. This enables the model to handle continuous signals, such as visual features. We further consider the case when there are multiple sequences that are semantically aligned at the sequence-level but not at the element-level (e.g. video and ASR), where we propose to use a Transformer to estimate the mutual information between the two sequences, which is again maximized via contrastive loss. We demonstrate the effectiveness of the learned representations on modeling long video sequences for action anticipation and video captioning. The results show that our method, referred to by Contrastive Bidirectional Transformer ({\bf CBT}), outperforms various baselines significantly. Furthermore, we improve over the state of the art.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05743](https://arxiv.org/abs/1906.05743)

##### PDF
[https://arxiv.org/pdf/1906.05743](https://arxiv.org/pdf/1906.05743)

