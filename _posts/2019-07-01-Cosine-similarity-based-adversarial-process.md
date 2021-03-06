---
layout: post
title: "Cosine similarity-based adversarial process"
date: 2019-07-01 04:44:35
categories: arXiv_AI
tags: arXiv_AI Adversarial Recognition
author: Hee-Soo Heo, Jee-weon Jung, Hye-jin Shim, IL-Ho Yang, Ha-Jin Yu
mathjax: true
---

* content
{:toc}

##### Abstract
An adversarial process between two deep neural networks is a promising approach to train a robust model. In this paper, we propose an adversarial process using cosine similarity, whereas conventional adversarial processes are based on inverted categorical cross entropy (CCE). When used for training an identification model, the adversarial process induces the competition of two discriminative models; one for a primary task such as speaker identification or image recognition, the other one for a subsidiary task such as channel identification or domain identification. In particular, the adversarial process degrades the performance of the subsidiary model by eliminating the subsidiary information in the input which, in assumption, may degrade the performance of the primary model. The conventional adversarial processes maximize the CCE of the subsidiary model to degrade the performance. We have studied a framework for training robust discriminative models by eliminating channel or domain information (subsidiary information) by applying such an adversarial process. However, we found through experiments that using the process of maximizing the CCE does not guarantee the performance degradation of the subsidiary model. In the proposed adversarial process using cosine similarity, on the contrary, the performance of the subsidiary model can be degraded more efficiently by searching feature space orthogonal to the subsidiary model. The experiments on speaker identification and image recognition show that we found features that make the outputs of the subsidiary models independent of the input, and the performances of the primary models are improved.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00542](http://arxiv.org/abs/1907.00542)

##### PDF
[http://arxiv.org/pdf/1907.00542](http://arxiv.org/pdf/1907.00542)

