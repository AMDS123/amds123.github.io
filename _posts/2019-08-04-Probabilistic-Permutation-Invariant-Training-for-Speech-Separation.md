---
layout: post
title: "Probabilistic Permutation Invariant Training for Speech Separation"
date: 2019-08-04 17:42:31
categories: arXiv_SD
tags: arXiv_SD
author: Midia Yousefi, Soheil Khorram, John H.L. Hansen
mathjax: true
---

* content
{:toc}

##### Abstract
Single-microphone, speaker-independent speech separation is normally performed through two steps: (i) separating the specific speech sources, and (ii) determining the best output-label assignment to find the separation error. The second step is the main obstacle in training neural networks for speech separation. Recently proposed Permutation Invariant Training (PIT) addresses this problem by determining the output-label assignment which minimizes the separation error. In this study, we show that a major drawback of this technique is the overconfident choice of the output-label assignment, especially in the initial steps of training when the network generates unreliable outputs. To solve this problem, we propose Probabilistic PIT (Prob-PIT) which considers the output-label permutation as a discrete latent random variable with a uniform prior distribution. Prob-PIT defines a log-likelihood function based on the prior distributions and the separation errors of all permutations; it trains the speech separation networks by maximizing the log-likelihood function. Prob-PIT can be easily implemented by replacing the minimum function of PIT with a soft-minimum function. We evaluate our approach for speech separation on both TIMIT and CHiME datasets. The results show that the proposed method significantly outperforms PIT in terms of Signal to Distortion Ratio and Signal to Interference Ratio.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.01768](https://arxiv.org/abs/1908.01768)

##### PDF
[https://arxiv.org/pdf/1908.01768](https://arxiv.org/pdf/1908.01768)

