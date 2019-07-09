---
layout: post
title: "BERT-DST: Scalable End-to-End Dialogue State Tracking with Bidirectional Encoder Representations from Transformer"
date: 2019-07-05 22:41:02
categories: arXiv_CL
tags: arXiv_CL Knowledge Ontology Tracking
author: Guan-Lin Chao, Ian Lane
mathjax: true
---

* content
{:toc}

##### Abstract
An important yet rarely tackled problem in dialogue state tracking (DST) is scalability for dynamic ontology (e.g., movie, restaurant) and unseen slot values. We focus on a specific condition, where the ontology is unknown to the state tracker, but the target slot value (except for none and dontcare), possibly unseen during training, can be found as word segment in the dialogue context. Prior approaches often rely on candidate generation from n-gram enumeration or slot tagger outputs, which can be inefficient or suffer from error propagation. We propose BERT-DST, an end-to-end dialogue state tracker which directly extracts slot values from the dialogue context. We use BERT as dialogue context encoder whose contextualized language representations are suitable for scalable DST to identify slot values from their semantic context. Furthermore, we employ encoder parameter sharing across all slots with two advantages: (1) Number of parameters does not grow linearly with the ontology. (2) Language representation knowledge can be transferred among slots. Empirical evaluation shows BERT-DST with cross-slot parameter sharing outperforms prior work on the benchmark scalable DST datasets Sim-M and Sim-R, and achieves competitive performance on the standard DSTC2 and WOZ 2.0 datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03040](http://arxiv.org/abs/1907.03040)

##### PDF
[http://arxiv.org/pdf/1907.03040](http://arxiv.org/pdf/1907.03040)

