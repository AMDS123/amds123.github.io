---
layout: post
title: "Repurposing Decoder-Transformer Language Models for Abstractive Summarization"
date: 2019-09-01 05:26:30
categories: arXiv_CL
tags: arXiv_CL Summarization Transfer_Learning Optimization Language_Model
author: Luke de Oliveira, Alfredo L&#xe1;inez Rodrigo
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network models have shown excellent fluency and performance when applied to abstractive summarization. Many approaches to neural abstractive summarization involve the introduction of significant inductive bias, exemplified through the use of components such as pointer-generator architectures, coverage, and partially extractive procedures, designed to mimic the process by which humans summarize documents. We show that it is possible to attain competitive performance by instead directly viewing summarization as a language modeling problem and effectively leveraging transfer learning. We introduce a simple procedure built upon decoder-transformers to obtain highly competitive ROUGE scores for summarization performance using a language modeling loss alone, with no beam-search or other decoding-time optimization, and instead relying on efficient nucleus sampling and greedy decoding.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00325](http://arxiv.org/abs/1909.00325)

##### PDF
[http://arxiv.org/pdf/1909.00325](http://arxiv.org/pdf/1909.00325)

