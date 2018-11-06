---
layout: post
title: "Neural CRF transducers for sequence labeling"
date: 2018-11-04 14:45:50
categories: arXiv_CL
tags: arXiv_CL RNN
author: Kai Hu, Zhijian Ou, Min Hu, Junlan Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional random fields (CRFs) have been shown to be one of the most successful approaches to sequence labeling. Various linear-chain neural CRFs (NCRFs) are developed to implement the non-linear node potentials in CRFs, but still keeping the linear-chain hidden structure. In this paper, we propose NCRF transducers, which consists of two RNNs, one extracting features from observations and the other capturing (theoretically infinite) long-range dependencies between labels. Different sequence labeling methods are evaluated over POS tagging, chunking and NER (English, Dutch). Experiment results show that NCRF transducers achieve consistent improvements over linear-chain NCRFs and RNN transducers across all the four tasks, and can improve state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01382](http://arxiv.org/abs/1811.01382)

##### PDF
[http://arxiv.org/pdf/1811.01382](http://arxiv.org/pdf/1811.01382)

