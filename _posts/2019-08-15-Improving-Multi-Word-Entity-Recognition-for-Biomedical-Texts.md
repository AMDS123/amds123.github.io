---
layout: post
title: "Improving Multi-Word Entity Recognition for Biomedical Texts"
date: 2019-08-15 18:04:39
categories: arXiv_CL
tags: arXiv_CL RNN Recognition
author: Hamada A. Nayel, H. L. Shashirekha, Hiroyuki Shindo, Yuji Matsumoto
mathjax: true
---

* content
{:toc}

##### Abstract
Biomedical Named Entity Recognition (BioNER) is a crucial step for analyzing Biomedical texts, which aims at extracting biomedical named entities from a given text. Different supervised machine learning algorithms have been applied for BioNER by various researchers. The main requirement of these approaches is an annotated dataset used for learning the parameters of machine learning algorithms. Segment Representation (SR) models comprise of different tag sets used for representing the annotated data, such as IOB2, IOE2 and IOBES. In this paper, we propose an extension of IOBES model to improve the performance of BioNER. The proposed SR model, FROBES, improves the representation of multi-word entities. We used Bidirectional Long Short-Term Memory (BiLSTM) network; an instance of Recurrent Neural Networks (RNN), to design a baseline system for BioNER and evaluated the new SR model on two datasets, i2b2/VA 2010 challenge dataset and JNLPBA 2004 shared task dataset. The proposed SR model outperforms other models for multi-word entities with length greater than two. Further, the outputs of different SR models have been combined using majority voting ensemble method which outperforms the baseline models performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05691](https://arxiv.org/abs/1908.05691)

##### PDF
[https://arxiv.org/pdf/1908.05691](https://arxiv.org/pdf/1908.05691)

