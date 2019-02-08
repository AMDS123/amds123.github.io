---
layout: post
title: "BERT and PALs: Projected Attention Layers for Efficient Adaptation in Multi-Task Learning"
date: 2019-02-07 15:05:46
categories: arXiv_CL
tags: arXiv_CL Attention
author: Asa Cooper Stickland, Iain Murray
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task learning allows the sharing of useful information between multiple related tasks. In natural language processing several recent approaches have successfully leveraged unsupervised pre-training on large amounts of data to perform well on various tasks, such as those in the GLUE benchmark. These results are based on fine-tuning on each task separately. We explore the multi-task learning setting for the recent BERT model on the GLUE benchmark, and how to best add task-specific parameters to a pre-trained BERT network, with a high degree of parameter sharing between tasks. We introduce new adaptation modules, PALs or `projected attention layers', which use a low-dimensional multi-head attention mechanism, based on the idea that it is important to include layers with inductive biases useful for the input domain. By using PALs in parallel with BERT layers, we match the performance of fine-tuned BERT on the GLUE benchmark with roughly 7 times fewer parameters, and obtain state-of-the-art results on the Recognizing Textual Entailment dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02671](http://arxiv.org/abs/1902.02671)

##### PDF
[http://arxiv.org/pdf/1902.02671](http://arxiv.org/pdf/1902.02671)

