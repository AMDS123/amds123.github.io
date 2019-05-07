---
layout: post
title: "Face Hallucination by Attentive Sequence Optimization with Reinforcement Learning"
date: 2019-05-04 15:01:57
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Attention Face Reinforcement_Learning Optimization
author: Yukai Shi, Guanbin Li, Qingxing Cao, Keze Wang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Face hallucination is a domain-specific super-resolution problem that aims to generate a high-resolution (HR) face image from a low-resolution~(LR) input. In contrast to the existing patch-wise super-resolution models that divide a face image into regular patches and independently apply LR to HR mapping to each patch, we implement deep reinforcement learning and develop a novel attention-aware face hallucination (Attention-FH) framework, which recurrently learns to attend a sequence of patches and performs facial part enhancement by fully exploiting the global interdependency of the image. Specifically, our proposed framework incorporates two components: a recurrent policy network for dynamically specifying a new attended region at each time step based on the status of the super-resolved image and the past attended region sequence, and a local enhancement network for selected patch hallucination and global state updating. The Attention-FH model jointly learns the recurrent policy network and local enhancement network through maximizing a long-term reward that reflects the hallucination result with respect to the whole HR image. Extensive experiments demonstrate that our Attention-FH significantly outperforms the state-of-the-art methods on in-the-wild face images with large pose and illumination variations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01509](http://arxiv.org/abs/1905.01509)

##### PDF
[http://arxiv.org/pdf/1905.01509](http://arxiv.org/pdf/1905.01509)

