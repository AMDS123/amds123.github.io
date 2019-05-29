---
layout: post
title: "DSReg: Using Distant Supervision as a Regularizer"
date: 2019-05-28 07:46:50
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification
author: Yuxian Meng, Muyu Li, Wei Wu, Jiwei Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we aim at tackling a general issue in NLP tasks where some of the negative examples are highly similar to the positive examples, i.e., hard-negative examples. We propose the distant supervision as a regularizer (DSReg) approach to tackle this issue. The original task is converted to a multi-task learning problem, in which distant supervision is used to retrieve hard-negative examples. The obtained hard-negative examples are then used as a regularizer. The original target objective of distinguishing positive examples from negative examples is jointly optimized with the auxiliary task objective of distinguishing softened positive (i.e., hard-negative examples plus positive examples) from easy-negative examples. In the neural context, this can be done by outputting the same representation from the last neural layer to different $softmax$ functions. Using this strategy, we can improve the performance of baseline models in a range of different NLP tasks, including text classification, sequence labeling and reading comprehension.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11658](https://arxiv.org/abs/1905.11658)

##### PDF
[https://arxiv.org/pdf/1905.11658](https://arxiv.org/pdf/1905.11658)

