---
layout: post
title: "Sequence-to-Sequence Learning as Beam-Search Optimization"
date: 2016-11-10 03:45:30
categories: arXiv_CV
tags: arXiv_CV Attention Optimization Language_Model
author: Sam Wiseman, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-Sequence (seq2seq) modeling has rapidly become an important general-purpose NLP tool that has proven effective for many text-generation and sequence-labeling tasks. Seq2seq builds on deep neural language modeling and inherits its remarkable accuracy in estimating local, next-word distributions. In this work, we introduce a model and beam-search training scheme, based on the work of Daume III and Marcu (2005), that extends seq2seq to learn global sequence scores. This structured approach avoids classical biases associated with local training and unifies the training loss with the test-time usage, while preserving the proven model architecture of seq2seq and its efficient training approach. We show that our system outperforms a highly-optimized attention-based seq2seq system and other baselines on three different sequence to sequence tasks: word ordering, parsing, and machine translation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.02960](https://arxiv.org/abs/1606.02960)

##### PDF
[https://arxiv.org/pdf/1606.02960](https://arxiv.org/pdf/1606.02960)

