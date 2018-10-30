---
layout: post
title: "On Controllable Sparse Alternatives to Softmax"
date: 2018-10-29 06:46:37
categories: arXiv_CL
tags: arXiv_CL Sparse Attention Summarization Classification
author: Anirban Laha, Saneem A. Chemmengath, Priyanka Agrawal, Mitesh M. Khapra, Karthik Sankaranarayanan, Harish G. Ramaswamy
mathjax: true
---

* content
{:toc}

##### Abstract
Converting an n-dimensional vector to a probability distribution over n objects is a commonly used component in many machine learning tasks like multiclass classification, multilabel classification, attention mechanisms etc. For this, several probability mapping functions have been proposed and employed in literature such as softmax, sum-normalization, spherical softmax, and sparsemax, but there is very little understanding in terms how they relate with each other. Further, none of the above formulations offer an explicit control over the degree of sparsity. To address this, we develop a unified framework that encompasses all these formulations as special cases. This framework ensures simple closed-form solutions and existence of sub-gradients suitable for learning via backpropagation. Within this framework, we propose two novel sparse formulations, sparsegen-lin and sparsehourglass, that seek to provide a control over the degree of desired sparsity. We further develop novel convex loss functions that help induce the behavior of aforementioned formulations in the multilabel classification setting, showing improved performance. We also demonstrate empirically that the proposed formulations, when used to compute attention weights, achieve better or comparable performance on standard seq2seq tasks like neural machine translation and abstractive summarization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11975](http://arxiv.org/abs/1810.11975)

##### PDF
[http://arxiv.org/pdf/1810.11975](http://arxiv.org/pdf/1810.11975)

