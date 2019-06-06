---
layout: post
title: "Strong and Simple Baselines for Multimodal Utterance Embeddings"
date: 2019-05-14 13:44:37
categories: arXiv_AI
tags: arXiv_AI Attention Embedding Inference Prediction
author: Paul Pu Liang, Yao Chong Lim, Yao-Hung Hubert Tsai, Ruslan Salakhutdinov, Louis-Philippe Morency
mathjax: true
---

* content
{:toc}

##### Abstract
Human language is a rich multimodal signal consisting of spoken words, facial expressions, body gestures, and vocal intonations. Learning representations for these spoken utterances is a complex research problem due to the presence of multiple heterogeneous sources of information. Recent advances in multimodal learning have followed the general trend of building more complex models that utilize various attention, memory and recurrent components. In this paper, we propose two simple but strong baselines to learn embeddings of multimodal utterances. The first baseline assumes a conditional factorization of the utterance into unimodal factors. Each unimodal factor is modeled using the simple form of a likelihood function obtained via a linear transformation of the embedding. We show that the optimal embedding can be derived in closed form by taking a weighted average of the unimodal features. In order to capture richer representations, our second baseline extends the first by factorizing into unimodal, bimodal, and trimodal factors, while retaining simplicity and efficiency during learning and inference. From a set of experiments across two tasks, we show strong performance on both supervised and semi-supervised multimodal prediction, as well as significant (10 times) speedups over neural models during inference. Overall, we believe that our strong baseline models offer new benchmarking options for future research in multimodal learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02125](http://arxiv.org/abs/1906.02125)

##### PDF
[http://arxiv.org/pdf/1906.02125](http://arxiv.org/pdf/1906.02125)

