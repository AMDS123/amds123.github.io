---
layout: post
title: "DDLSTM: Dual-Domain LSTM for Cross-Dataset Action Recognition"
date: 2019-04-18 08:17:35
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN RNN Recognition
author: Toby Perrett, Dima Damen
mathjax: true
---

* content
{:toc}

##### Abstract
Domain alignment in convolutional networks aims to learn the degree of layer-specific feature alignment beneficial to the joint learning of source and target datasets. While increasingly popular in convolutional networks, there have been no previous attempts to achieve domain alignment in recurrent networks. Similar to spatial features, both source and target domains are likely to exhibit temporal dependencies that can be jointly learnt and aligned. 
 In this paper we introduce Dual-Domain LSTM (DDLSTM), an architecture that is able to learn temporal dependencies from two domains concurrently. It performs cross-contaminated batch normalisation on both input-to-hidden and hidden-to-hidden weights, and learns the parameters for cross-contamination, for both single-layer and multi-layer LSTM architectures. We evaluate DDLSTM on frame-level action recognition using three datasets, taking a pair at a time, and report an average increase in accuracy of 3.5%. The proposed DDLSTM architecture outperforms standard, fine-tuned, and batch-normalised LSTMs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08634](http://arxiv.org/abs/1904.08634)

##### PDF
[http://arxiv.org/pdf/1904.08634](http://arxiv.org/pdf/1904.08634)

