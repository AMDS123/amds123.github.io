---
layout: post
title: "Adversarial Generation and Encoding of Nested Texts"
date: 2019-06-01 15:01:16
categories: arXiv_CL
tags: arXiv_CL Adversarial Text_Generation Language_Model Prediction
author: Alon Rozental
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a new language model called AGENT, which stands for Adversarial Generation and Encoding of Nested Texts. AGENT is designed for encoding, generating and refining documents that consist of a long and coherent text, such as an entire book, provided they are hierarchically annotated (nested). i.e. divided into sentences, paragraphs and chapters. The core idea of our system is learning vector representations for each level of the text hierarchy (sentences, paragraphs, etc...), and train each such representation to perform 3 tasks: The task of reconstructing the sequence of vectors from a lower level that was used to create the representation, and generalized versions of the Masked Language Modeling (MLM) and "Next Sentence Prediction" tasks from BERT Devlin et al. [2018]. Additionally we present a new adversarial model for long text generation and suggest a way to improve the coherence of the generated text by traversing its vector representation tree.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00238](http://arxiv.org/abs/1906.00238)

##### PDF
[http://arxiv.org/pdf/1906.00238](http://arxiv.org/pdf/1906.00238)

