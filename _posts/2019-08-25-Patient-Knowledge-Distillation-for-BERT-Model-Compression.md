---
layout: post
title: "Patient Knowledge Distillation for BERT Model Compression"
date: 2019-08-25 16:13:24
categories: arXiv_CL
tags: arXiv_CL Knowledge Language_Model
author: Siqi Sun, Yu Cheng, Zhe Gan, Jingjing Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Pre-trained language models such as BERT have proven to be highly effective for natural language processing (NLP) tasks. However, the high demand for computing resources in training such models hinders their application in practice. In order to alleviate this resource hunger in large-scale model training, we propose a Patient Knowledge Distillation approach to compress an original large model (teacher) into an equally-effective lightweight shallow network (student). Different from previous knowledge distillation methods, which only use the output from the last layer of the teacher network for distillation, our student model patiently learns from multiple intermediate layers of the teacher model for incremental knowledge extraction, following two strategies: ($i$) PKD-Last: learning from the last $k$ layers; and ($ii$) PKD-Skip: learning from every $k$ layers. These two patient distillation schemes enable the exploitation of rich information in the teacher's hidden layers, and encourage the student model to patiently learn from and imitate the teacher through a multi-layer distillation process. Empirically, this translates into improved results on multiple NLP tasks with significant gain in training efficiency, without sacrificing model accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09355](http://arxiv.org/abs/1908.09355)

##### PDF
[http://arxiv.org/pdf/1908.09355](http://arxiv.org/pdf/1908.09355)

