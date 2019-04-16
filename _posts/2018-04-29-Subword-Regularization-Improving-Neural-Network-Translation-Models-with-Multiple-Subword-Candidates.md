---
layout: post
title: "Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates"
date: 2018-04-29 16:13:44
categories: arXiv_CL
tags: arXiv_CL Regularization Segmentation NMT Language_Model
author: Taku Kudo
mathjax: true
---

* content
{:toc}

##### Abstract
Subword units are an effective way to alleviate the open vocabulary problems in neural machine translation (NMT). While sentences are usually converted into unique subword sequences, subword segmentation is potentially ambiguous and multiple segmentations are possible even with the same vocabulary. The question addressed in this paper is whether it is possible to harness the segmentation ambiguity as a noise to improve the robustness of NMT. We present a simple regularization method, subword regularization, which trains the model with multiple subword segmentations probabilistically sampled during training. In addition, for better subword sampling, we propose a new subword segmentation algorithm based on a unigram language model. We experiment with multiple corpora and report consistent improvements especially on low resource and out-of-domain settings.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.10959](https://arxiv.org/abs/1804.10959)

##### PDF
[https://arxiv.org/pdf/1804.10959](https://arxiv.org/pdf/1804.10959)

