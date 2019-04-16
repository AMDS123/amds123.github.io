---
layout: post
title: "Top-down Tree Structured Decoding with Syntactic Connections for Neural Machine Translation and Parsing"
date: 2018-09-06 07:33:48
categories: arXiv_CL
tags: arXiv_CL Attention NMT RNN
author: Jetic Gū, Hassan S. Shavarani, Anoop Sarkar
mathjax: true
---

* content
{:toc}

##### Abstract
The addition of syntax-aware decoding in Neural Machine Translation (NMT) systems requires an effective tree-structured neural network, a syntax-aware attention model and a language generation model that is sensitive to sentence structure. We exploit a top-down tree-structured model called DRNN (Doubly-Recurrent Neural Networks) first proposed by Alvarez-Melis and Jaakola (2017) to create an NMT model called Seq2DRNN that combines a sequential encoder with tree-structured decoding augmented with a syntax-aware attention model. Unlike previous approaches to syntax-based NMT which use dependency parsing models our method uses constituency parsing which we argue provides useful information for translation. In addition, we use the syntactic structure of the sentence to add new connections to the tree-structured decoder neural network (Seq2DRNN+SynC). We compare our NMT model with sequential and state of the art syntax-based NMT models and show that our model produces more fluent translations with better reordering. Since our model is capable of doing translation and constituency parsing at the same time we also compare our parsing accuracy against other neural parsing models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.01854](https://arxiv.org/abs/1809.01854)

##### PDF
[https://arxiv.org/pdf/1809.01854](https://arxiv.org/pdf/1809.01854)

